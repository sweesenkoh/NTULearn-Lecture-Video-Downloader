# NTULearn-Lecture-Video-Downloader
This script helps to download NTU Lecture Video in a convenient way. This script will start by asking for ntulearn username and password. Using the information, it will show all the current modules you are taking and you can select any one of them to start downloading. 
</br>
## Below are some dependencies to install before running: 
Run these line by line in terminal or command prompt. 

```
pip3 install selenium
pip3 install bs4
```

</br>

## Usage Guide: 

Download the python file and place it in a directory. To use it, navigate to the directory in terminal or command prompt. For example, if the python file is placed in Desktop Folder, we can navigate to the Desktop directory by running the following line in terminal:

```
cd Desktop
```
Next, to run the file, simply type the following line:

```
python3 NTULectureVideoDownloaderConsoleApp.py 
```
</br>

To avoid entering the credentials information during every launch, you can directly hardcode your credentials details into the code. In the top section of the code, you will find the following snippet:

```
...

#Enter Credentials information here

username = None
password = None

##

...
```


In this section, replace the None values with your actual credentials information, below is an example:
```

#Enter Credentials information here

username = 'sweesenkoh@student.main.ntu.edu.sg'
password = 'MyAmazingPassword'

##

```
</br></br>


## Below is demo of how the console app looks like:
<img width="666" alt="image" src="https://user-images.githubusercontent.com/48687942/65212365-6392d580-dad4-11e9-9181-0650319e134b.png">

<img width="655" alt="image" src="https://user-images.githubusercontent.com/48687942/65212429-a359bd00-dad4-11e9-9e92-812ef1bfeffa.png">

</br>

### Can download all available videos in one click

</br>
<img width="676" alt="image" src="https://user-images.githubusercontent.com/48687942/65214099-41e91c80-dadb-11e9-8d34-3d0243cd6f9a.png">


