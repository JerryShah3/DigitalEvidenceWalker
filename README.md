# Digital Evidence Walker - Automated Forensics Tool

There are tools available to find the evidences but they have certain drawbacks. Every tool cannot do everything so to overcome that drawback I have developed this automated tool and it is CLI based. It has 43 different modules for finding evidences.
<br><br>
<b>Some Different Features :</b>
<br>
<h6><i>
1. Whirlpool hash calculation <br>
2. Tiger hash calculation <br>
3. Image-Metadata <br>
4. File entropy calculation <br>
5. Extract information on hardware configuration <br>
6. File index number calculation <br>
7. Hash Identification <br>
8. Checking Disk Space <br>
</i></h6><br>

The tool has been developed using shell script because it allows us to program commands in chains and have the system execute them as a scripted event, just like batch files. They also allow for far more useful functions, such as command substitution.
<br><br>
<b>Tools and Technologies :</b>
<br><br>
I have used many pre-installed commands of kali linux which makes it easy to use. As kali linux is mainly used for Penetration Testing and Digital Forensics, this tool is compatible with many Debian Systems. There are many things that I have added/downloaded manually which helps in digital forensics investigation, thus making it easy for investigators.
<br><br>
<b>Downloaded/Added Technologies :</b>
<br>
<h6>
1. ImageMagick – for extracting image metadata <br>
2. Lshw – for extracting information on hardware configuration <br>
3. Rockyou.txt File – for brute forcing the password files <br>
</h6>
<br>
<b>Limitations :</b>
<h6>
1. Compatible with Ubuntu after downloading some dependencies <br>
2. Not compatible with Windows <br>
3. Not compatible with MacOS <br>
</h6>
<br>

<b>Dependencies for Ubuntu :</b>
<br><br>
How to install ? <br>

Use command on terminal : sudo apt-get install <package-name> <br>

Example : sudo apt-get install imagemagick <br><br>
<h6>
1. Imagemagick <br>
2. Hash-identifier <br>
3. Hashdeep (if not available in ubuntu) <br>
4. Lshw <br>
5. Unshadow (if not available in ubuntu) <br>
6. John (john-the-ripper) <br>
7. Binwalk <br>
8. Objdump <br>
9. Volatility (if not available in ubuntu) <br>
</h6>
<br><br>
<b>Best Compatible Debian Flavours :</b>
<br>
<h6>
1. Kali <br>
2. BackBox <br>
3. Parrot OS <br>
4. BlackArch <br>
5. Bugtraq <br>
6. DEFT <br>
7. Santoku <br>
8. Pentoo <br>
9. CAINE <br>
10. Network Security Toolkit <br>
12. Fedora Security Spin <br>
13. ArchStrike
</h6>
<br><br>

<b>How to run :</b>

<br>
 1. Go to terminal and type the command <b><i>git clone https://github.com/ShreyJerry333/DigitalEvidenceWalker.git </b></i><br>
 2. After Downloading type the command cd DigitalEvidenceWalker <br>
 3. Run the command <b><i>chmod +x DigitalEvidenceWalker</b></i><br>
