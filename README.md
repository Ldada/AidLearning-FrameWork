# AidLearning <br>
[![License](https://img.shields.io/badge/license-BSD--3--Clause-blue.svg)](https://github.com/Yoline777/AidLearning/blob/master/license.md) 
thank for <b>qidiso</b> provide the [中文说明](https://www.jianshu.com/p/f6ec13ece792)

Aid Learning builds a Linux system with graphical interface on Android mobile phone, and supports GUI, Python and AI programming. This means that when it is installed, your Android phone has a Linux system in which you can run Gui programs of python and AI. Aid Learning supports a list of Top Machine Learning Framework for Deep Learning. Now we support Caffe, Tensorflow, Mxnet, ncnn, Keras, Pytorch,Gluoncv, cv2,scipy.... powerfully build-in. (in order to support deep learning, you no longer need complex configuration and wall-flipping dependency packages).

Furthermore we provide an AI coding develop tool named Aid_code. It can provide you a visual AI programming IDE by using Python from zero on our framework! It means that when it is installed, your Android phone owned a Linux system with GUI which can write and run AI program in it as same as in PC. In addition,Latest version(>0.72) of Aid Learning can provide a new visual programming experience of <b>touch-and-drag</b> by using Python on our framework (supporting both Python 2 and Python 3)!

At the same time, Aid Learning provides wifi-based mapping projection technology, which can project the code of mobile phone to PC and interact with SSH remote commands. It can also be projected to TV and projector for large screen display.

In short, Aid Learning has created a Four-in-one and  touch-and-drag platform for rapid development and learning of Android+Linux+AI+Python. It can not only use mobile phones for fragmented programming, but also make full use of the development advantages of the two main operating systems (Android+Linux) and the perfect AI terminal advantages of mobile phones. With this advantage, Aid Learning can build a perfect learning ecosphere of programming education.

<img src="logo.png" style="width: 500px; height: auto; margin-left: 50px; " /> <br>

AidLearning is a Linux system running on the Android with GUI, AI and  Python support . <a href="http://www.aidlearning.net" >The AidLearning </a> project which have the <b>Linux+Anroid+AI 3IN1</b> environments Developed and Maintained by several students from [Cas University](http://english.cas.cn) and [Yale University](https://www.yale.edu).
<hr>




Now you have a complete linux with GUI running on Android (Real linux running on the busybox and not virtul environment. So it is faster and almost real-time.) and can write your AI code on it visually using the Python!
<br> <br>

<b>Now Release: AidLearning 0.73</b>
<br> What's new:
<br>
1.  Fixed the bug that <b>apt update</b> failed (ps:The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 8B48AD62925553 NO_PUBKEY 7638D0442B90D010 NO_PUBKEY EF0F382A7B6500)
2.  AiCode has major updates:

- The interface and menu were redesigned to fix the bug of floating menu occlusion code.
- New code auto-prompting function, if you input the initial letters of variables, functions and keywords, the system will <b>automatically complete</b> , which can greatly improve efficiency.
- New ui Design Interface (Wizard), now ui design does not require you to write ui code , you can use <b>touch and drag </b>Components to generate ui codes. We have built-in a large number of UI development components，the system will automatically generate ui code, you only need to focus on the core processing code.

3.  Redesign the example codes and use the new ui Design method.

4.  Because of the importing of touch and drag programming, the development code now adopts the method of separating the ui interface from the personal core processing code. The ui interface code is generated by the system, and the core processing code system also generates the port, you can focus on the part you really want to deal with.

5.  Fixed the problem of relying on a small amount of network traffic. Now even if your mobile phone is in flight mode, it can run the system.

6.  Update other bugs that affect stability



<b> Update log: AidLearning 0.70-0.72</b>
<br> What's update:
<br>
- Full support for <b>Python 3 and python 2</b>, as well as pip3 and pip2 install <br>
- <b>Caffe/MXNET/Gluoncv/Tensorflow/ Keras/Pytorch/Opencv4</b>
   for Python3 and Python2  are perfectly supported  <br>
- With the new CVS package, you can easily customize your interface with Python code:
    
    cvs. setTitle ("Face Recognize")<br>
    cvs. setInput_dict (usr_dict)<br>
    cvs. setSubmitName ("Register your FaceID")<br>
    cvs. setCamX (350,480)<br>
    cvs. setInfoX (320,60)<br>
    
- Now You can use **apt (apt-get)** to install new packages to improve your Linux Environment... <br>
- Some BUGs have been solved, such as:
    <br>Press the home key to return home and then enter the app: Instead of returning to the GUI, the problem is returning to the terminal.<br>
    Reducing dependence on network traffic.<br>
- Adding new buttons for running Python 3 and python 2 online for **Aid_code IDE** <br>
- Add the ***AI Example Center***, put some examples on the website, the new examples can be downloaded from the website in the future, in order to prevent the distribution of installation packages too large.<br>
- Modified accounts that do not activate the mailbox can be logged in **directly**, but there are prompts to activate the interface after login...
 <br>  <br>
<br>

<h3><b><u>TABLE OF CONTENTS</u></b></h3>
<a href="#dependencies" >&#9635 Dependencies</a><br>
<a href="#installation" >&#9635 Installation</a><br>
<a href="#Support" >&#9635 Support AI framework</a><br>
<a href="#GUI" >&#9635 GUI Customize</a><br>
<a href="#ssh" >&#9635 SSH (connect to pc)</a><br>
<a href="#Feature" >&#9635 Main Features</a><br>
<a href="#youtobe" >&#9635 Youtobe show</a><br>
<a href="#ScreenShot" >&#9635 Screenshot of AidLearning</a><br>
<a href="#Examples" >&#9635 Examples Inside</a><br>
<a href="#aidcode" >&#9635 Aid_code IDE</a><br>
<a href="#contributors" >&#9635 Contributors</a><br>
<a href="#ref" >&#9635 References</a><br>


<br><br>

<div id="dependencies"></div>
<h3><b><u>Dependencies</u></b></h3>All you need is an Android devices (phone ,tablet or arm board)  that supports the CPU of Arm64(aarch64). The Android version requires more than 6.0. If you think the parameters are not clear enough, I would like to say that most of the mainstream mobile phones support it, such as Samsung, Huawei, MI, OPPO, VIVO, etc.In addition, the requirement of storage space is a little big. It is suggested that there should be 4G free storage space.


<div id="installation"></div>
 <h3><b><u>Installation</u></b></h3> To install AidLearing, Simply download an app (apk file) and install it on your mobile device. download at:<br>
 http://www.aidlearning.net/downloads/aidlux-05-10.apk (support python2.7, python3 not support) <br> 
 http://www.aidlearning.net/downloads/aidlux-05-31.apk (support python2.7 and python3.5.1) <br> 
 http://www.aidlearning.net/downloads/aidlux-06-01.apk (support  python2.7 and python3.6.4)<br> 
 
 http://www.aidlearning.net/downloads/aidlux-06-28.apk (support  python2.7 and python3.6.4,support the touch and drag ui design,support automatic code completion)<br> 
 
 The  app （apk） is only 8M，when you install the apk ,the apk will download the depdence of the linux
is 700M and 350M examples of AI codes using python. all is about 1G size to download .So it's recommended that you install it in a WiFi environment.
<br><br>

<div id="Support"></div>
<h3><b><u>Support AI Framework</u></b></h3>

---

* [Caffe]https://github.com/BVLC/caffe
* [Tensorflow]https://github.com/tensorflow/tensorflow
* [Mxnet]https://github.com/apache/incubator-mxnet
* [Keras]https://github.com/keras-team/keras
* [ncnn]https://github.com/Tencent/ncnn
* [pytorch]https://github.com/pytorch/pytorch
* [opencv]https://github.com/opencv/opencv

<p align="center">
	<img src="screen4.jpg"  width="400" >
</p>

---








<div id="GUI"></div>
<h3><b><u>GUI Customize</u></b></h3>

<p><div style="width: 600px;" >
          <p><i><b>Now you can easily customize your GUI with touch and drag！Wizard will produce the code automatic:</b></i></p>
<p><i>    

class MyApp(App):
    def __init__(self, *args):
        super(MyApp, self).__init__(*args)

    def main(self):
        container = gui.VBox(width=120, height=100)
        self.lbl = gui.Label('Hello world!')
        self.bt = gui.Button('Press me!')

        # setting the listener for the onclick event of the button
        self.bt.onclick.do(self.on_button_pressed)

        # appending a widget to another, the first argument is a string key
        container.append(self.lbl)
        container.append(self.bt)

        # returning the root widget
        return container

    # listener function
    def on_button_pressed(self, widget):
        self.lbl.set_text('Button pressed!')
        self.bt.set_text('Hi!')

</i></p>
	<p align=center>
          <img src="Wizard.gif" width=200px />
	</p>
    </div> <br>

<p>
As shown in the figure above, we divide an app into four areas: Title area, camera area, input area, info show area. An app display can consist of one or more areas.You can use Python (cvs class) statements to manipulate the Title, size and layout of these areas.
for examples： in the info area ,you can do this:<br>
cvs. setInfoX (320,60) # setting the width,height of the info area<br>
cvs. infoshow ("this is info show") # show info in the info area<br>
</p>
In particular, input area, we greatly simplify the operation process, you only need to specify a dict, AidLeaning will automatically generate a form for you to interact with users, such as you need to register a face, you can do this:
<br><br>
usr_dict={'username': '', 'type': 'add_person'}# define the input list<br><br>
cvs.setInput_dict(usr_dict)# setting for gui<br><br>
cvs.setSubmitName("Register your FaceID")#setting the name of submit button<br><br>
so ,aidlearning will produce this gui:
<p align=center>
<img src="input.png" width=200px  />
</p>



<a href="https://github.com/aidlearning/AidLearning-FrameWork/blob/master/cvs/README.md" ><button style="font-size: 20px; color: white; background-color: steelblue; height: 50px; border-radius: 10px; " > >>> Tutorial & Guide </button></a>

<br>

<div id="ssh"></div>
<h3><b><u>SSH (connect to PC) </u></b></h3>

<p><br>
PC can connect to mobile by using **ssh-keygen**. Generate a new key pair with <b>ssh-keygen</b> command in your PC.  the command ssh-keygen produce the file of id_rsa and id_rsa.pub in the dir: ~/.ssh/

Just need you do: open the url:mobilephone'sip:8910/upload(for example:http://192.168.1.6:8910/upload) in the pc to upload ssh's file(id_rsa and id_rsa.pub). 

<img src="ssh.png" width=300px />


</p>






<div id="Feature"></div>
<h3><b><u>Main Features: </u></b></h3>

# Graphical User Interface
We fixed Graphical User Interface for the Linux on Andorid(It has been pruned by andorid!), so you can use the GUI just like on the pc. For instance, You can use opencv to open and view camera!
<p align="center">
	<img src="up.png"  width="200" >
</p>

# Fast,Real-Time
Real linux running on the busybox and not virtul environment like VirtulBox. So it is faster and almost real-time

# Easy to use
We provide a plenty of examples and by using our framework, you can run it with a tap, and then get a visual log to show the informations or errors.
<p align="center">
	<img src="screen2.jpg"  width="400" >
</p>

# Coding anywhere
You can coding on your phone anywhere, anytime. Every inch of fragmentation have been fully utilized. Your creativity can be instantly realized with a flash of inspiration.
<p align="center">
	<img src="screen3.jpg"  width="400" >
</p>
# Energy Star

According to the test on the mainstream smartphone like Samsung, Aid Learning Framework only use 1% power consumption in a whole day (Standby)

<br><br>

<div id="youtobe"></div>
<h3><b><u>Youtobe show </u></b></h3>
<p >
[Watch the video](https://youtu.be/bkvNXgCi3_c)
</p>

<br> <br>

<div id="ScreenShot"></div>
<h3><b><u>ScreenShot of AidLearning</u></b></h3>
<p align="center">
	<img src="Screen_11.jpg"  width="400" >
</p>
<p align="center">
	<img src="Screenshot_10.jpg"  width="600" >
</p>

<div id="Examples"></div>
 <h3><b><u>Examples Inside:</u></b></h3>

<p>Facencnn(mobiefacenet ncnn) 15fps in mobile phone
<p>Face Landmark (106 keypoints ncnn) 15fps  in mobile phone
<p>handpose (tensorflow ) 5fps  in mobile phone
<p>body posenet for single person(converted from google ) 10fps  in mobile phone
<p>body posenet for multi-person(converted from google ) 7fps  in mobile phone
<p>Stylized picture(GAN ) 3fps in mobile phone
.....
<p align="center">
<img src="screen21.jpg" align = "center" width="200" >
</p>




<div id="aidcode"></div>
 <h3><b><u>Aid_code IDE of python </u></b></h3>
We provide an AI coding develop tool named Aid_code. It can provide you a visual AI programming IDE by using Python from zero on our framework! Using the tool, you can run your python2 or python3 codes online.so ,you can coding with Aid_code IDE on your phone anywhere, anytime. 
<p align="center">
	<img src="screen3.jpg"  width="400" >
</p>
Of course, you can use Aid_code on the web to edit your code online. For example, you can use web coding with Aid_code on PC. You just need to open the web address: IP of your mobile phone:8900/, when your PC and mobile phone are in the same LAN.
You can open it on a PC, for example:<br><br>
Http://192.168.1.8:8900/, if your phone's IP is 192.168.1.8, you can check your phone's IP by commanding ifconfig (run ifconfig under terminal)
<p>
	<img src="web.png" width="500" >
<p>
 <br><br>

<div id="contact"></div>
 <h3><b><u>Contributors</u></b></h3>
We are inviting anyone who wishes to contribute to the <b>AidLearning</b> project to reach to us. We primarily need contributions in translating the documentation of the project's code to major languages that includes but not limited to French, Spanish, Portuguese, Arabian and more. We want every developer and researcher around the world to benefit from this project irrespective of their native languages. <br>

We give special thanks to <b>[qidiso](https://github.com/qidiso/)</b> for his incredible and excellent work in translating <b>AidLearning</b>'s documentation to the Chinese language. Find below the contact details of those who have contributed immensely to the <b>AidLearning</b> project.

<p>
    <i>Email: </i>    <a style="text-decoration: none;"  href="mailto:postmaster@aidlearning.com">postmaster@aidlearning.com</a> <br>
      <i>Website: </i>    <a style="text-decoration: none;" target="_blank" href="http://www.aidlearning.net"> http://www.aidlearning.net</a> <br>
</p>



 </p>

 <br>

[Medium-- Stories about AidLearning](https://medium.com/@sxg628/aidlearning-build-a-linux-system-running-on-the-android-with-gui-ai-and-python-support-a90b6c2ded34)

 <div id="ref"></div>
 <h3><b><u>References</u></b></h3>

* VTE (libvte): Terminal emulator widget for GTK+, mainly used in gnome-terminal. [Source](https://github.com/GNOME/vte), [Open Issues](https://bugzilla.gnome.org/buglist.cgi?quicksearch=product%3A%22vte%22+), and [All (including closed) issues](https://bugzilla.gnome.org/buglist.cgi?bug_status=RESOLVED&bug_status=VERIFIED&chfield=resolution&chfieldfrom=-2000d&chfieldvalue=FIXED&product=vte&resolution=FIXED).
* iTerm 2: OS X terminal application. [Source](https://github.com/gnachman/iTerm2), [Issues](https://gitlab.com/gnachman/iterm2/issues) and [Documentation](http://www.iterm2.com/documentation.html) (which includes [iTerm2 proprietary escape codes](http://www.iterm2.com/documentation-escape-codes.html)).
* Konsole: KDE terminal application. [Source](https://projects.kde.org/projects/kde/applications/konsole/repository), in particular [tests](https://projects.kde.org/projects/kde/applications/konsole/repository/revisions/master/show/tests), [Bugs](https://bugs.kde.org/buglist.cgi?bug_severity=critical&bug_severity=grave&bug_severity=major&bug_severity=crash&bug_severity=normal&bug_severity=minor&bug_status=UNCONFIRMED&bug_status=NEW&bug_status=ASSIGNED&bug_status=REOPENED&product=konsole) and [Wishes](https://bugs.kde.org/buglist.cgi?bug_severity=wishlist&bug_status=UNCONFIRMED&bug_status=NEW&bug_status=ASSIGNED&bug_status=REOPENED&product=konsole).
* hterm: JavaScript terminal implementation from Chromium. [Source](https://github.com/chromium/hterm), including [tests](https://github.com/chromium/hterm/blob/master/js/hterm_vt_tests.js), and [Google group](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-hterm).
* xterm: The grandfather of terminal emulators. [Source](http://invisible-island.net/datafiles/release/xterm.tar.gz).
* Connectbot: Android SSH client. [Source](https://github.com/connectbot/connectbot)
* Android Terminal Emulator: Android terminal app which Termux terminal handling is based on. Inactive. [Source](https://github.com/jackpal/Android-Terminal-Emulator).
* Termux: Android terminal and Linux environment - app repository. [Source](https://github.com/termux/termux-app).
* remi:Python REMote Interface library. Platform independent. In about 100 Kbytes, perfect for your diet.[Source]
(https://github.com/dddomodossola/remi).
* [Caffe]https://github.com/BVLC/caffe
* [Tensorflow]https://github.com/tensorflow/tensorflow
* [Mxnet]https://github.com/apache/incubator-mxnet
* [Keras]https://github.com/keras-team/keras
* [ncnn]https://github.com/Tencent/ncnn
* [pytorch]https://github.com/pytorch/pytorch
* [opencv]https://github.com/opencv/opencv
