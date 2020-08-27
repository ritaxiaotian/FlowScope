# Atteion, if you are a student, read this part first. 
# FlowScope 

Implementation code of the algorithm described in FlowScope: Spotting Money Laundering Based on Graphs. and thanks for the contribution of the coworkers , i.e. , Shenghua Liu and Zifeng Li.

**FlowScope**: Spotting Money Laundering Based on Graphs

**FlowScope** is developped for ML detection based on multipartite graph,  which models the high-volume *flows* of funds  through chains of bank accounts, and  detects the complete flow of money from source to destination.

## Abstract 

Given a graph of the money transfers between accounts of a bank, how can we detect  money laundering? Money laundering refers to criminals using the bank's services to move massive amounts of illegal money to untraceable destination accounts, in order to inject their illegal money into the legitimate financial system. Existing graph fraud detection approaches focus on dense subgraph detection, without considering the fact that money laundering involves high-volume *flows* of funds through chains of bank accounts, thereby decreasing their detection accuracy.  Instead, we propose to model the transactions using a multipartite graph, and  detect the complete flow of money from source to destination using a scalable algorithm, FlowScope. Theoretical analysis shows that FlowScope provides guarantees in terms of the amount of money that fraudsters can transfer  without being detected. FlowScope outperforms state-of-the-art baselines in accurately detecting the accounts involved in money laundering, in both injected and real-world data settings.

## Run in command line

Code in  FlowScope-AMC:

```
        designed for detecting money laundering with one middle layer M
```

Code in  FlowScope-AM1M2C:

```
        designed for detecting money laundering with two middle layers M1 and M2.  
```

for usage:

```
        python2  FS.py  input_dir output_dir  block_num 
```
       
parameter specifications：

```
        input_dir:  the path to input data; 
        output_dir: the path to output result;
        block_num:  numbers of suspicious transactions you want to detect;
```

  input data: decribe the transaction between two  adjacent layer, which should be named as fs1.csv, fs2.csv ... fsn.csv . 
              

```
        fs1.csv: describes the transactions between source layer and the first middle layer. 
        ...
        fsi.csv: describes the transactions between current i-th layer and the next layer. 
        ...
        fsn.csv: describes the transactions between last middle layer and the destination layer.  
```

  ouput result: the most suspicous accouts in each layer. 

```
        rown.csv: the source  account of the n-th suspicious transactions；
        coln.csv: the destination  account of the n-th suspicious transactions；
        midk_n. csv: the middle account in k-th middle layer of the n-th suspicious transactions；
```


## The results  

<p align="center">
  <img src="images/results2.jpg" height="800"  />
</p>

## Cite:

```
@inproceedings{li2020flowscope,
  title        = {FlowScope: Spotting Money Laundering Based on  Graphs },
  author       = {Xiangfeng Li, Shenghua Liu, Zifeng Li, Xiaotian Han, Chuan Shi , Bryan Hooi, He Huang, Xueqi Cheng},
  booktitle    = {in Proceedings of the AAAI Conference on Artificial Intelligence},
  year         = {2020},
  organization = {AAAI}
}

```







# Stop doing this:

​    Stop doing this  !!!!!!!!!!!!!!!!!!!!!!!!!!!!  Software engineer is a better choice !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!     

I wish you could stop doing this, anti-money laundering(AML) is useless. you can search the top AML company，such as LexisNexis(it has some business about AML ),  Analysing its annual report，you will know that devote your career to AML is a total mistake.   Maybe, a job of software engineer is a better choice. 

## AML is worthless

   If a person can build a car, why he choose to repair a car? Do you think this man some how was not smart.  Yes back to this question, the most import thing in a company is profit, if the work you do is related to the core profits, your payment, your feature will be brighter, if you do other jobs, you are insignificant, the meaning of your existence is only to support the core department. 

   In the bank, why you choose AML, the core business of the bank is loan business. AML does not create any  direct  profit for the bank, so  if the government not force the bank do some AML, you existence have no value.  There are so many better job than AML in bank, such as software engineer.  You can learning about the salary of AML job, you will know I am suggesting you for a better feature.  

## my experience

   I am work so long with this in the school, and has no prejudice about this research before, but when I am about to graduate and want to find a job, I realized it was a big mistake, I can not find good internship,  good job, my classmates gets several times  salary than me. Even I work hard than them in the school, even they play game everyday.  Once, a  human resource throws my resume onto my face at once after browse it, I really don't know where I went wrong， and I spent countless sleepless night during my last year in the school. All of above is the total truth that I experienced, I hope you not follow my way. It was a total false. 
    The experiment in the paper is really time costing, because of no data was opened on the net with labeled money laundering group. So many injection experiments are needed. I spent two week working day and night using 4 computer servers just trying one model. And it takes a long time to came up with the model, and we try dozens of models before published in the paper. Be honest, we tune the model from the beginning to the end of the whole research, you can image how many time I spent on this work. And the most unacceptable thing is I even cannot find a half pay job compared to the classmates who play game all day, there are very few companies who are interest in my paper. 

## why I don't stop

My supervisors push me so hard with this job, describe a bright future for me, even threatened me with failure to graduate. I am a honest man and a bit timid.  So you can image how many efforts I put on this useless work, and how I suffered from this. But when I seek my teacher for help with the work, they reject to help to me or they provide bad jobs which I should get sleeping all three years in my school life without this fucking work.  Where's my supervisors? They have already made profit from this paper, and there are still some my efforts in their profit . They won't share whatever you do.

The question is that despite they made billions of money from it, they did not share 1$ with me or help me to get a good job. Do you know what you do while do the AML work?  you are wasting your best time in your life and you cannot find good job, you feature will be gloomy. Where's your supervisors? They take no responsibility for your future, they just try to make money out of you, out of your work. Contrast with your bad work, they just have made another profit. Hope you can get a good supervisor in your life.

## the revenue of top AML company 

if you do not believe me, looking at the  annual report of the parent company of  LexisNexis， RELX， it is easy to find on the net. LexisNexis is a top company  in AML,  its mainly business operators in Europe and North America, where the financial system is quite mature, and the governments pay more attentions to the AML problem.  It total revenue about risk solution and  business analytics is only 2,316 million ￡. Yes, and the AML's revenue is just a part of it, showing as the picture below.

![image](https://user-images.githubusercontent.com/59363655/90001747-66864e00-dcc4-11ea-9f27-257c299feed6.png)

Stop doing this  !!!!!!!!!!!!!!!!!!!!!!!!!!!!  Software engineer is a better choice !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!     

## what AML company need

### how much the banks value AML

​    Though AML is a complex problem,  and you might think that the government and banks put so much attention to it, that's not the truth.  AML does  not create any profit directly, so for the company you work for, the value of AML equals to the fine they  receives. You might say that,  AML has great social and economic significance. That's a big joke, all your company your boss need is profit, is money, you are too young too simple, and may have not get fucke	 by the society and life.  The existence  meaning of regular  department in the bank is not to loan money to who can not pay back, or interact with whom that will make them get in trouble.  

​     Ride the rubbish thoughts out of your mind, the biggest problem for the bank, for any company is profit. 

### the  fine they receive 

​     You can easily search on the net, and get the below information.  in China, the total amount of the fine of thousands of financial company is no more than 1  billion due to poor performance in AML ,   even in Europe and North America, Australia, where the financial market is quite measure,  the amount of  is not high compare to their high profit.  

The bank has no strong motivation to do AML.

![1598500597707](C:\Users\alf\AppData\Roaming\Typora\typora-user-images\1598500597707.png)



### what they do 

You might think that, the bank will check every  transaction carefully.  Yes, you are wrong again.  The bank only checks  the transactions which money amount is very high or only interested in some people, some companies, some groups with specific topology. For banks, to please big customers, they will give up some examinations  and for effectiveness purpose.  For banker, to  save time and leave enough of time to make profit, they just 'check' the  suspicious  transactions   on the computer and then turn it  to ‘normal’.  If there were no especially suspicious transactions, they won't pay attention, this is why  there are some many obvious money laundering behaviors was not known until the fine was imposed on the bank. You can imagine that there are still so many money laundering behavior without be caught.

### ![1598503665451](C:\Users\alf\AppData\Roaming\Typora\typora-user-images\1598503665451.png)

### AML tools in the bank 

The government has  made many laws  which describe what is money laundering. For the bank,  pick the suspicious transaction out that  the government wants is enough, so the main  AML system is based on rules designed according to the laws  government has made.  

Despite you have many good ideas about AML, for the bank, it was useless,  the existence AML system is enough, who want do more but get no pay? 

Yes, may your algorithm is accurate, the  existence AML system can do 80% of it,  yours do 100%. but what is  the meaning of it, saving a little bit of money for the 20% money forfeited by  government, the bank earns a big deal of money every day, who has time to think about it.  Moreover, If your algorithm run a bit slow,  why the bank use your algorithm?  The bank just sum the amount of transactions during two people, and select and check the most biggest  amount  of transactions from database, they can find most of  money laundering behaviors.  Even some of small amount of transactions is exactly  money laundering behaviors,  how is that?  The government has no time to care about this tiny problem, and will not punish the bank.  

 the  existence AML system tools is enough, as you can see,  the police still has a crime solving rate indicator. 

### Dataset problem 

The experiment in the paper is really time costing, because of no data was opened on the net with labeled money laundering group. So many injection experiments are needed. I spent two week working day and night using 4 computer servers just trying one model. And it takes a long time to came up with the model, and we try dozens of models before published in the paper. Be honest, we tune the model from the beginning to the end of the whole research, you can image how many time I spent on this work. And the most unacceptable thing is I even cannot find a half pay job compared to the classmates who play game all day, there are very few companies who are interest in my paper. 

### my suggestion 

Stop doing this  !!!!!!!!!!!!!!!!!!!!!!!!!!!!  Software engineer is a better choice !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!     









