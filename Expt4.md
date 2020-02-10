##### Experiment No:4

##   Shell programming


>  ### 4.1   Aim
 Write shell script to show various system configuration like

- Currently logged user and his login name
- Current shell
- Home directory
- Operating system type
- Current path setting
- Current working directory
- Number of users currently logged in. 
>  ### 4.2 Shellscript 

	clear
	log=`who|wc -l`
	ostype=$OSTYPE
	echo "os type is $ostype"
	echo "the currently logged in user is $USER"
	echo "the current shell is $SHELL"
	echo "the home directory is $HOME"
	echo "the current path is $PATH"
	echo "the working directory is $PWD"
	echo "there are $log users logged in"

 >  ### 4.3 Sample input & output
  ![N|Solid](https://raw.githubusercontent.com/VUASWATHY/LAB_RECORD/master/ext4opt.png)

  



  ### 4.4 Result
  The shell script for displaying various system configurations were made and the output was verified.




