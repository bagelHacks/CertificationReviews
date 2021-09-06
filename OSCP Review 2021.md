# OSCP Review 2021

### Audience
Hello, this post is for those who are considering taking this certification as well as those interested in the resources I used to prepare for this battle.  

### Whoami

My name is Beyviel, and I currently work as a Cyber Threat Analyst for an MSSP. I fell in love with computer's when I started my journey in late 2017 and some of the certifications I hold are Sec+, CCNA, CYSA, and EJPT. I heard about the OSCP from a coworker, and after reading many online review's I decided that this would be something I would enjoy. I was casually studying for this starting July of 2020, but once I finished school in December of 2020, I got serious and passed on my first attempt in July, 2021. 

### Preparation 

I failed plenty of times training for the exam, but the key is persistence. I spent about 4 hours on the weekdays and 8 hours during the weekends hacking away. At one point, my local coffee shop offered me a job to work once every two weeks so that I can get free coffee. 

I started by taking the "Practical Ethical Hacking" (PEH) course by Heath Adams (The Cyber Mentor). This is a quality course, and for 30$ it is one of the best. Heath is a great teacher and I really enjoyed the Active Directory section. This was not very important to the exam, but relevant to working in a SOC. This course also covered exploiting Buffer Overflow's which is guaranteed to be on the exam. 

Next, I went to TryHackMe and finished the "Complete Beginner" and the "Offensive Pentesting" paths. This requires an $8 subscription, but gave me confidence rooting boxes. This had a lot of hand holding, but covers lots of technique in a nice structured way. The Buffer Overflow room gave me lots of practice developing exploit code.

I went back and completed the Heath Adam's Linux and Privilege escalation coursed on Udemy. You can probably tell that I'm a huge fan and for good reason. These courses gave a strong foundation for privilege escalation which was needed. Watching these courses alone is not enough. 

Next, I spent some time doing VirtualHackingLabs. I bought a three month pass and picked up both of the Certificate of Completions after finishing most of the machines. These were very good quality, and I liked how much detail the PDF included. The downside is that there were not many Windows boxes and I had more kernel escalations then any other privilege escalation method. Repetition is necessary for building a good methodology and by the end, I had a good web application approach.

By this time, I was feeling more confident. I knew that I had the BOF down, I just needed to get better at privilege escalation. 
I went for Offensive Security Proving Grounds labs, which costed $20 a month. These are more difficult then the exam (and difficult for me). I needed hints/walkthroughs for many of these machines, but I learned a ton. By this time, I was happy with my privilege escalation methodology. 

Around this time, I bought 60 days of lab time which included the OSCP exam. I did about 15 of the machines, but I did not like how unstructured it was. I was spoiled from THM, Proving Grounds and VirtualHackingLabs. 

Instead, I decided to schedule my exam and move to HackTheBox. I played HTB during PEH and had a difficult experience with easy boxes. This time, I was able to complete machines with minimal hints. I went after the recommended OSCP boxes by TJ Null which had plenty of machines more difficult then the exam.

I used OneNote to document every box I rooted and learned lots of cool tricks along the way such as TMUX shortcuts, bash one liner's and nice methodology in my head. Before the exam, I made sure that I filled the reporting template with what I could and then reviewed until exam day. 

### Exam Day
I scheduled my exam for Saturday morning at 8 am. I went to sleep the night before around 11 pm, and was feeling good. I did not have any issues setting up and showing off my 4 monitor setup to the proctors. When the exam started, I used autorecon to start the service scans on all the targets in the background while I tackled the Buffer Overflow. This took me about 2.5 hours which was longer then I expected. No big deal, I took a break and continued on. By the time it was 3am, I had a foothold on every machine, and needed 2 more escalations to get 100%. I stayed two more hours and I could'nt figure it out and completed my exam around 5 am. As I was taking the exam, I kept telling myself "The battle is just getting started". I was also listening to hyped up music and took plenty of snack breaks. 

I slept for about 4 hours and spent the next day writing my report which ended up being almost 100 pages. I made sure to detail every command and meaning of every argument I used. I turned the report in and received confirmation that I passed 2 days later. All the Glory to God for this opportunity and blessing.

### Results 

Preparing for this test was one of the best choices for my career. Performing all of the different hacking techniques raised my technical understanding of cyber attacks. Working as a Cyber Defender, I would see different attacks and think "Oh I've done this one before". I think this test is good for anyone who can afford the time commitment. My knowledge working in the field helped, but I think even someone without any previous I.T. knowledge can ace this exam. With plenty of inexpensive learning options to choose from I am happy that this knowledge can be learned even without buying the exam. 

### Resources

https://academy.tcm-sec.com/p/practical-ethical-hacking-the-complete-course

https://tryhackme.com/path/outline/beginner

https://tryhackme.com/path/outline/pentesting

https://academy.tcm-sec.com/p/windows-privilege-escalation-for-beginners

https://academy.tcm-sec.com/p/linux-privilege-escalation

https://www.virtualhackinglabs.com/

https://www.offensive-security.com/labs/individual/

https://app.hackthebox.eu/invite

https://www.netsecfocus.com/oscp/2021/05/06/The_Journey_to_Try_Harder-_TJnull-s_Preparation_Guide_for_PEN-200_PWK_OSCP_2.0.html (HTB Recommended Boxes)

