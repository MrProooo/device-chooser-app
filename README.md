# device-chooser-app
APP H DOSTO
//variables
var name;
var email;
var password;
var a;
var b = 0;
var email1;
var password1;

//Extra things
hideElement("button2");

hideElement("text_area12");

//Events
onEvent("text_input1","click",function(){
  b = b + 1;
  Btn();
});
onEvent("text_input2","click",function(){
  b = b + 1;
  Btn();
});
onEvent("text_input4","click",function(){
  b = b + 1;
  Btn();
  showElement("button2");
});
onEvent("text_input1","input",function(){
  email = getText("text_input1");
});
onEvent("text_input4","input",function(){
  password = getText("text_input4");
});
onEvent("text_input2","input",function(){
  name = getText("text_input2");
});
onEvent("button2","click",function(){
  setScreen("loginpage");
});
onEvent("text_input3","input",function(){
  email1 = getText("text_input3");
});
onEvent("text_input6","input",function(){
  password1 = getText("text_input6");
});
onEvent("button1","click",function(){
  if(password1 == password && email1 == email){
    setScreen("mainpage1");
    setText("text_area16","Welcome "+name+", To Our Device Chooser app Pls Choose Which Device You Want Below");
  }
  else{
    showElement("text_area12");
  }
});
onEvent("button4","click",function(){
  setText("text_area18","Hello "+name+", Pls Choose The Company of which you want ur PC");
});
onEvent("button82","click",function(){
  setText("text_area18","Hello "+name+", Pls Choose The Company of which you want ur Laptop");
});
onEvent("button4","click",function(){
  setScreen("Pcpage");
});
onEvent("image37"||"image40"||"image43"||"image47","click",function(){
  setScreen("Pcpage");
});
onEvent("image43","click",function(){
  setScreen("Pcpage");
});
onEvent("image47","click",function(){
  setScreen("Pcpage");
});
onEvent("image40","click",function(){
  setScreen("Pcpage");
});
onEvent("image52","click",function(){
  setScreen("mainpage1");
});
onEvent("image53","click",function(){
  setScreen("loginpage");
});
onEvent("button5","click",function(){
  setScreen("Laptoppage");
});
onEvent("image58","click",function(){
  setScreen("mainpage1");
});
onEvent("button7","click",function(){
  setScreen("tabpage");
});

//hp 

onEvent("button8","click",function(){
  setScreen("hp");
});
onEvent("button16","click",function(){
  setScreen("hp1");
});
onEvent("button17","click",function(){
  setScreen("hp2");
});
onEvent("button18","click",function(){
  setScreen("hp3");
});
onEvent("button3","click",function(){
  setScreen("hp4");
});
onEvent("image48"||"image49"||"image50"||"image51","click",function(){
  setScreen("hp");
});
onEvent("image49","click",function(){
  setScreen("hp");
});
onEvent("image50","click",function(){
  setScreen("hp");
});
onEvent("image51","click",function(){
  setScreen("hp");
});

//apple

onEvent("button9","click",function(){
  setScreen("apple");
});
onEvent("button12","click",function(){
  setScreen("apple1");
});
onEvent("button13","click",function(){
  setScreen("apple2");
});
onEvent("button14","click",function(){
  setScreen("apple3");
});
onEvent("image36","click",function(){
  setScreen("apple");
});
onEvent("image00","click",function(){
  setScreen("apple");
});
onEvent("image39","click",function(){
  setScreen("apple");
});

//dell

onEvent("button11","click",function(){
  setScreen("dell");
});
onEvent("button19","click",function(){
  setScreen("dell1");
});
onEvent("button20","click",function(){
  setScreen("dell2");
});
onEvent("button21","click",function(){
  setScreen("dell3");
});
onEvent("image45","click",function(){
  setScreen("dell");
});
onEvent("image44","click",function(){
  setScreen("dell");
});
onEvent("image46","click",function(){
  setScreen("dell");
});

//asus

onEvent("button10","click",function(){
  setScreen("asus");
}); 
onEvent("button15","click",function(){
  setScreen("asus1");
});
onEvent("button22","click",function(){
  setScreen("asus2");
});
onEvent("image41","click",function(){
  setScreen("asus");
});
onEvent("image42","click",function(){
  setScreen("asus");
});

//hp laptop

onEvent("button25","click",function(){
  setScreen("hplaptop");
});
onEvent("button29","click",function(){
  setScreen("hplaptop1");
});
onEvent("button30","click",function(){
  setScreen("hplaptop2");
});
onEvent("button31","click",function(){
  setScreen("hplaptop3");
});
onEvent("button32","click",function(){
  setScreen("hplaptop4");
});
onEvent("image33","click",function(){
  setScreen("hplaptop");
});
onEvent("image65","click",function(){
  setScreen("hplaptop");
});
onEvent("image68","click",function(){
  setScreen("hplaptop");
});
onEvent("image73","click",function(){
  setScreen("hplaptop");
});
onEvent("image64","click",function(){
  setScreen("Laptoppage");
});

//apple laptop

onEvent("button26","click",function(){
  setScreen("applelaptop");
});
onEvent("button36","click",function(){
  setScreen("applelaptop1");
});
onEvent("button37","click",function(){
  setScreen("applelaptop2");
});
onEvent("button38","click",function(){
  setScreen("applelaptop3");
});
onEvent("image86","click",function(){
  setScreen("applelaptop");
});
onEvent("image88","click",function(){
  setScreen("applelaptop");
});
onEvent("image90","click",function(){
  setScreen("applelaptop");
});
onEvent("image84","click",function(){
  setScreen("Laptoppage");
});

//dell laptop

onEvent("button23","click",function(){
  setScreen("delllaptop");
});
onEvent("button24","click",function(){
  setScreen("delllaptop1");
});
onEvent("button33","click",function(){
  setScreen("delllaptop2");
});
onEvent("button34","click",function(){
  setScreen("delllaptop3");
});
onEvent("button35","click",function(){
  setScreen("delllaptop4");
});
onEvent("image92","click",function(){
  setScreen("delllaptop");
});
onEvent("image94","click",function(){
  setScreen("delllaptop");
});
onEvent("image96","click",function(){
  setScreen("delllaptop");
});
onEvent("image98","click",function(){
  setScreen("delllaptop");
});
onEvent("image79","click",function(){
  setScreen("Laptoppage");
});

//asus laptop

onEvent("button27","click",function(){
  setScreen("asuslaptop");
}); 
onEvent("button43","click",function(){
  setScreen("asuslaptop1");
});
onEvent("button44","click",function(){
  setScreen("asuslaptop2");
});
onEvent("button45","click",function(){
  setScreen("asuslaptop3");
});
onEvent("button46","click",function(){
  setScreen("asuslaptop4");
});
onEvent("image113","click",function(){
  setScreen("asuslaptop");
});
onEvent("image115","click",function(){
  setScreen("asuslaptop");
});
onEvent("image117","click",function(){
  setScreen("asuslaptop");
});
onEvent("image119","click",function(){
  setScreen("asuslaptop");
});
onEvent("image111","click",function(){
  setScreen("Laptoppage");
});

//lenovo laptop

onEvent("button28","click",function(){
  setScreen("lenovo");
}); 
onEvent("button39","click",function(){
  setScreen("lenovo1");
});
onEvent("button40","click",function(){
  setScreen("lenovo2");
});
onEvent("button41","click",function(){
  setScreen("lenovo3");
});
onEvent("button42","click",function(){
  setScreen("lenovo4");
});
onEvent("image100","click",function(){
  setScreen("lenovo");
});
onEvent("image104","click",function(){
  setScreen("lenovo");
});
onEvent("image102","click",function(){
  setScreen("lenovo");
});
onEvent("image106","click",function(){
  setScreen("lenovo");
});
onEvent("image83","click",function(){
  setScreen("Laptoppage");
});

//samsung tab

onEvent("button25","click",function(){
  setScreen("hplaptop");
});
onEvent("button29","click",function(){
  setScreen("hplaptop1");
});
onEvent("button30","click",function(){
  setScreen("hplaptop2");
});
onEvent("button31","click",function(){
  setScreen("hplaptop3");
});
onEvent("button32","click",function(){
  setScreen("hplaptop4");
});
onEvent("image33","click",function(){
  setScreen("hplaptop");
});
onEvent("image65","click",function(){
  setScreen("hplaptop");
});
onEvent("image68","click",function(){
  setScreen("hplaptop");
});
onEvent("image73","click",function(){
  setScreen("hplaptop");
});
onEvent("image64","click",function(){
  setScreen("Laptoppage");
});

//apple tab

onEvent("button48","click",function(){
  setScreen("appletab");
});
onEvent("button51","click",function(){
  setScreen("appletab1");
});
onEvent("button52","click",function(){
  setScreen("appletab2");
});
onEvent("button53","click",function(){
  setScreen("appletab3");
});
onEvent("image54","click",function(){
  setScreen("appletab");
});
onEvent("image88","click",function(){
  setScreen("appletab");
});
onEvent("image90","click",function(){
  setScreen("appletab");
});
onEvent("image84","click",function(){
  setScreen("tabpage");
});

//lenovo tab

onEvent("button23","click",function(){
  setScreen("delllaptop");
});
onEvent("button24","click",function(){
  setScreen("delllaptop1");
});
onEvent("button33","click",function(){
  setScreen("delllaptop2");
});
onEvent("button34","click",function(){
  setScreen("delllaptop3");
});
onEvent("button35","click",function(){
  setScreen("delllaptop4");
});
onEvent("image92","click",function(){
  setScreen("delllaptop");
});
onEvent("image94","click",function(){
  setScreen("delllaptop");
});
onEvent("image96","click",function(){
  setScreen("delllaptop");
});
onEvent("image98","click",function(){
  setScreen("delllaptop");
});
onEvent("image79","click",function(){
  setScreen("Laptoppage");
});

//Functions
function Btn(){
  if(b == 3){
  showElement("button2");
}
}
