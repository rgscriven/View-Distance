This is to allow players to change their view distance

Installation
Move the Veiw Distance folder to the Apps folder

inside XM8Apps_Init.sqf change the app you want to use to 

//App 1
_app1Text = "View Distance";
_app1Logo = getText (configfile >> "CfgWeapons" >> "Binocular" >> "picture");
app1_action = {
  execVM "xm8Apps\Apps\View Distance\VeiwDistance.sqf";
};


The distance change is on lines 9 to 13