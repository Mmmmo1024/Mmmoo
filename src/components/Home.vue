<template>
  <div id="main">
      <div class="baseLayout">
        <div class="resume">
          <div class="head">
            <span>P</span><span>E</span><span>R</span><span>S</span><span>O</span></span><span>N</span><span>A</span><span>L</span><br>
            <span>R</span><span>E</span><span>S</span><span>U</span><span>M</span><span>E</span>          
          </div>
          <div class="info">
            <div class="box">
              <div class="name">
                <span>莫桂江</span>
              </div>
              <div class="will">
                <span>求职意向：前端工程师</span>
              </div>
            </div>
            <div class="box">
              <div class="baseInfo">
                <span>年龄：23</span><span>籍贯：广西钦州</span><br>
                <span>学历：本科</span><span>专业：软件工程</span><br>
                <span>QQ：997905119</span><span>电话：18589990280</span><br>
              </div>
            </div>
          </div>
            <canvas id="myCanvas1" width="155px" height="200px"></canvas> 
            <canvas id="myCanvas2" width="300px" height="200px"></canvas>   
            <canvas id="myCanvas3" width="170px" height="200px"></canvas>     
            <div class="headImg"></div>
            <canvas id="myCanvas4" width="200px" height="150px"></canvas>    
            <canvas id="myCanvas5" width="200px" height="150px"></canvas>  
            <canvas id="myCanvas6" width="300px" height="150px"></canvas>
            <div class="education">
              <span>教育背景</span>
              <div class="text">
                <p>2015-9~~2019-6|广西科技大学</p>
                <p>主修课程：c语言、java程序设计、oracle大型数据库、数据结构、计算机网络、软件工程导论等</p>
              </div>
            </div>   
            <div class="skill">
              <span>个人技能</span>
              <div class="text" >
                <div class="progress"><span>HTML</span><el-progress :show-text="false" :stroke-width="13" :percentage="60"></el-progress></div>
                <div class="progress"><span>CSS3</span><el-progress :show-text="false" :stroke-width="13" :percentage="50" color="rgba(142, 113, 199, 0.7)"></el-progress></div>
                <div class="progress"><span>VUE</span><el-progress :show-text="false" :stroke-width="13" :percentage="40" color="#00FF7F"></el-progress></div>
                <div class="progress" ><span>JS</span><el-progress :show-text="false" :stroke-width="13" :percentage="40" color="#FF6347"></el-progress></div>
                <div class="progress" ><span>JQUERY</span><el-progress :show-text="false" :stroke-width="13" :percentage="20" color="#FFA500"></el-progress></div>
              </div>
            </div>  
            <div class="like">
              <span>兴趣爱好</span>
              <div class="text">
                <p>
                  喜欢听音乐，唱歌，也喜欢运动，尤其是打篮球，平时也喜欢逛逛技术论坛，或者是手机类的论坛（因为平时爱鼓捣手机）
                </p>
              </div>
            </div>
            <div class="evaluate">
              <span>自我评价</span>
              <div class="text">
                <p style="width: 300px;margin-left: 100px;text-align: left;">    
                   本人性格热情开朗，待人友好，为人诚实谦虚。工作勤奋，认真负责，能吃苦耐劳，有一定的沟通能力。
                   热爱前端开，渴望汲取新知识，自学能力强。
                </p>
              </div>
            </div>
            <div class="work">
              <span>实习经验</span>
              <div class="text">
                <span>2018-7~~2019-5|广西犇云科技股份有限公司</span><span style="margin-left: 100px">职位：前端工程师</span>
                <p>项目：<容易投资管理流程服务平台></p>
                <p>运用了Vue2.0+elementUi框架，负责平台页面搭建以及与后台的数据交互</p>
                <p style="margin-left: 50px"><大学了没></p>
                <p>运用了Vue3.0+elementUi框架，负责大学了没子系统实训系统的页面搭建以及与后台的数据交互</p>
              </div>
            </div>
            <div class="imgbox"><img src="../assets/weChart.jpg" style="width: 150px;height: 150px"></div>
        </div>
      </div>
  </div>
</template>
<script>
  export default{
    name:'resume',
    data(){
      return{

      }
    },
    methods:{

    },
    created:function(){
      setTimeout(function(){
        let canvas1=document.getElementById('myCanvas1');
        let ctx1=canvas1.getContext('2d');
        ctx1.beginPath();
        ctx1.strokeStyle ='#6fc643';
        ctx1.lineWidth=6
        ctx1.moveTo(0,5);
        ctx1.lineTo(50,5);
        ctx1.lineTo(150,120);
        ctx1.lineTo(80,200);
        ctx1.stroke(); 

        let canvas2=document.getElementById('myCanvas2');
        let ctx2=canvas2.getContext('2d');
        ctx2.beginPath();
        ctx2.strokeStyle ='#e1432a';
        ctx2.lineWidth=6
        ctx2.moveTo(0,130);
        ctx2.lineTo(110,130);
        ctx2.lineTo(175,195);
        ctx2.lineTo(295,112);
        ctx2.lineTo(295,80);
        ctx2.stroke();

        let canvas3=document.getElementById('myCanvas3');
        let ctx3=canvas3.getContext('2d');
        ctx3.beginPath();
        ctx3.strokeStyle ='#5cc8ca';
        ctx3.lineWidth=6
        ctx3.moveTo(20,190);
        ctx3.lineTo(20,90);
        ctx3.lineTo(130,10);
        ctx3.lineTo(160,10);
        ctx3.stroke(); 

        let canvas4=document.getElementById('myCanvas4');
        let ctx4=canvas4.getContext('2d');
        ctx4.beginPath();
        ctx4.strokeStyle ='#4b5ca1';
        ctx4.lineWidth=6
        ctx4.moveTo(0,5);
        ctx4.lineTo(20,40);
        ctx4.lineTo(180,40);
        ctx4.lineTo(180,140);
        ctx4.stroke(); 

        let canvas5=document.getElementById('myCanvas5');
        let ctx5=canvas5.getContext('2d');
        ctx5.beginPath();
        ctx5.strokeStyle ='#b82736';
        ctx5.lineWidth=6
        ctx5.moveTo(0,140);
        ctx5.lineTo(40,140);
        ctx5.lineTo(120,3);
        ctx5.lineTo(200,70);
        ctx5.stroke(); 

        let canvas6=document.getElementById('myCanvas6');
        let ctx6=canvas6.getContext('2d');
        ctx6.beginPath();
        ctx6.strokeStyle ='#f1842f';
        ctx6.lineWidth=6
        ctx6.moveTo(5,95);
        ctx6.lineTo(5,75);
        ctx6.lineTo(100,75);
        ctx6.lineTo(175,0);
        ctx6.lineTo(250,110);
        ctx6.lineTo(300,110);
        ctx6.stroke();
          },1000)
      
    }
  }
</script>
<style scoped>
p{
  margin-top: 0px;
  margin-bottom:5px;
}
.head{
  padding: 20px;
  font-size: 40px;
  font-weight: bolder;
  margin-bottom: 10px
}
.head span{
  font-weight: normal;
  display: inline-block;
  margin:0px 30px 10px 0px
}
.resume{
  background:#e7e9e8;
  position: relative;
  padding-bottom: 120px
}
.info{
  overflow: auto;
}
.info .box{
  width: 50%;
  float: left;
}
.box .name{
  width: 50%;
  margin: auto;
  padding:10px 0px;
  font-size: 33px;
  color: #000;
  text-align: left; 
  border-bottom: 3px solid black;
}
.box .will{
  width: 50%;
  margin: auto;
  padding:10px 0px;
  font-size: 25px;
  color: #000;
  text-align: left;
  font-weight: normal;
}
.box .baseInfo{
  line-height: 45px;
  font-size:18px;
}
.box .baseInfo span{
  display: inline-block;
  width: 180px;
  text-align: left;
}
#myCanvas1{
  position: relative;
  left:105px;
  top: 60px 
}
#myCanvas2{
  position: relative;
  top: 50px;
  left:115px;
}
#myCanvas3{
  position: relative;
  right: 32px;
  top: 180px 
}
#myCanvas4{
  position: relative;
  left:40px;
  bottom: 200px 
}
#myCanvas5{
  position: relative;
  right:105px;
  bottom: 50px 
}
#myCanvas6{
  position: relative;
  right:95px;
  bottom: 55px
}

.headImg{
  border-radius: 120px;
  height: 230px;
  width: 230px;
  border: 1px solid black;
  background: url('') -545px -860px no-repeat;
  background-size: ;
  margin: auto;
}
.text{
  font-size: 17px;
  margin-top: 20px;
  overflow: auto;
}
.education{
  width: 370px;
  background: url('../assets/education.png') 230px 0px  no-repeat ;
  background-size: 9%;
  position: absolute;
  top: 360px;
  left:20px;
}
.education span{
  display: inline-block;
  width: 100px;
  line-height: 30px;
  text-align: center;
  background: #019443;
  color: #fff;
  margin-right: 25px
}
.skill{
  width: 400px;
  background: url('../assets/skill.png') 190px -1px  no-repeat ;
  background-size: 7%;
  position: absolute;
  top: 490px;
  right: 0px;
  overflow: auto;
}
.skill>span{
  display: inline-block;
  width: 100px;
  line-height: 30px;
  text-align: center;
  background: #00adec;
  color: #fff;
  margin-left: 150px
}
.like{
  width: 300px;
  text-align: left;
  background: url('../assets/like.png') 130px -2px no-repeat ;
  background-size: 13%;
  position: absolute;
  bottom: 315px;
  left:20px;
  
}
.like span{
  display: inline-block;
  width: 100px;
  line-height: 30px;
  text-align: center;
  background: #800080;
  color: #fff;
  margin-left: 30px
}
.work{
  width: 600px;
  text-align: left;
  background: url('../assets/work.png') 160px 2px no-repeat ;
  background-size: 5%;
  position: absolute;
  top: 800px;
  left:330px;
}
.work .text>p{
  margin-top: 5px;
  margin-bottom: 0px
}
.work>span{
  display: inline-block;
  width: 100px;
  line-height: 30px;
  text-align: center;
  background: #FF6347;
  color: #fff;
  margin-left: 50px
}

.evaluate{
  width: 400px;
  text-align: right;
  background: url('../assets/evaluate.png') 260px 0px no-repeat ;
  background-size: 10%;
  position: absolute;
  top: 320px;
  right: 260px
}
.evaluate span{
  display: inline-block;
  width: 100px;
  line-height: 30px;
  text-align: center;
  background: #DC143C;
  color: #fff;
}
.skill .text{
  margin-top: 55px
}
.skill .text .progress{
  overflow: auto;
  margin-bottom: 10px;
}
.skill .text .progress>span{
  display: inline-block;
  float: left;
  width: 60px;
  margin:0px 10px 0px 100px;
}
.imgbox{
  position: absolute;
  left: 30px;
  bottom: 30px
}
</style>
<style>
.el-progress{
  width: 200px;
  float: left;
  padding-top: 3px
}
 .el-progress-bar__outer{ 
  background: #fff;
} 
</style>