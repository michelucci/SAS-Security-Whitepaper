## SAS Security Whitepaper 

This document contains a best practice method describing how to implement metadata security in [SAS®](https://www.sas.com/de_ch/home.html). The document "Metadata Security in SAS® – Step-by-Step" (_Jørgensen & Hoffritz_, 2013) has been used as basis for this one. The goal of this paper is to outline a simpler and more streamlined version of metadata security when the number of people working with SAS is small (of the order of 20-30) and are divided in less than 10 groups. 

The small amount of people and groups allow to simplify heavily the metadata security structure that we should implement.  I will not describe how to do specific operations in SAS (like creating a user or a group) since tools change and new versions come often and assume that the reader has some knowledge on the working of the tool (in particular of the Management Console as I write). Our aim is to describe a methodology that will get you started regardless of what version of SAS you are using, and that will avoid problems along the road in the future. Additionally note that the aim of this paper is not to give a complete overview on how security in SAS® works. I will describe only a few features, the one we need to implement our best practice methods and nothing more. I will use a "lazy approach" and describe only what I need. The best practices have been reviewed by J. Fritzenwallner from SAS®.

### Download

The file can be downloaded here: <a href="https://github.com/michelucci/SAS-Security-Whitepaper/blob/master/Metadata%20Security%20in%20SAS%209.4%20-%20Best%20Practice%20an%20easy%20start.pdf" >SAS Security Whitepaper Download</a>.

### Support and contact

In case you need any additional information or have questions don't hesitate to contact me at my 
[mail](mailto:umberto.michelucci@gmail.com).

### References

Jørgensen, J. & Hoffritz, C., 2013. http://support.sas.com. [Online]
Available at: http://support.sas.com/resources/papers/proceedings11/376-2011.pdf
[Accessed 22nd August 2016].
