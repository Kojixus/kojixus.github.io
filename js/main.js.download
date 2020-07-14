var tday=new Array("sunday","monday","tuesday","wednesday","thursday","friday","saturday");
var tmonth=new Array("january","february","march","april","may","june","july","august","september","october","november","december");

function GetClock(){
var d=new Date();
var nday=d.getDay(),nmonth=d.getMonth(),ndate=d.getDate();
var nhour=d.getHours(),nmin=d.getMinutes(),nsec=d.getSeconds();
if(nmin<=9) nmin="0"+nmin
if(nsec<=9) nsec="0"+nsec;

document.getElementById('date').innerHTML=""+tday[nday]+", "+tmonth[nmonth]+" "+ndate+"";
document.getElementById('time').innerHTML=" "+nhour+":"+nmin+":"+nsec+"";
}


window.onload=function(){
GetClock();
setInterval(GetClock,1000);
}

