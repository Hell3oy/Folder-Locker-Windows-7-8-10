# Folder-Locker-Windows-7-8-10
### Discription
  > lock ur any windows 7, 8, 10 folder

### Before Use This File Must Do This Changes
  - Open this file in notepad and change ur password in following code
  - In the Below Code there is writen a ***EnterUrPasswordHere*** instead of ***EnterUrPasswordHere*** write ur password and save it in the formate of .bat extention
  - :UNLOCK
    echo Enter password to unlock folder
    set/p "pass=>"
    if NOT %pass%== ***EnterUrPasswordHere*** goto FAIL
    attrib -h -s "HTG Locker"
    ren "HTG Locker" Locker
    echo Folder Unlocked successfully
    goto End
