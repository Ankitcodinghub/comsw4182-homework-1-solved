# comsw4182-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [COMSW4182 Homework 1 Solved](https://www.ankitcodinghub.com/product/comsw4182-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94524&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMSW4182 Homework 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Problem 1: Password Cracker

An attacker exploited an unknown zero-day vulnerability to steal some entries of /etc/shadow from a remote server. Meanwhile, he or she happened to know the length of these leaked passwords and their possible character sets through some sophisticated social engineering. The victims on that remote server were lazy and refused to set up long passwords with some special characters, which is a bad yet common practice for many people in real world. However, this gives attacker a great chance to quickly crack their passwords. You task is to write a simple password cracker in C or C++ to find out their passwords.

(a) The passwords are to be 8 numerical digits(i.e., 0-9), representing users’ birth date. The encryption algorithm used to compute the hash is sha512. So the equation to compute the hash is sha512(password|salt), where | denotes the string concatenation.

(b) The passwords are to be 6 characters(including all possible upper and lower case letters i.e., a-zA-Z). The encryption algorithm used to compute the hash is sha3 512. So the equation to compute the hash is sha3 512(password|salt), where | denotes the string concatenation.

Hint:

<ul>
<li style="list-style-type: none;">
<ul>
<li>You will be given a /etc/shadow which contains user name, salt, password hash and other informtaion. Figure out the format of /etc/shadow before you get started.</li>
<li>You might notice that the generated hash may contain some non-printable characters. In order to represent them into a text file, they are converted into base64 encoding. In /etc/shadow, all password hashes are represented in base64 format. The padding characters ”=” at the tail of base64-encoded hashes are removed.</li>
<li>Use encryption function of OpenSSL library to compute the hash.</li>
<li>Consider to use parallel computing to boost your password cracker by splitting the task into multiple
sub-tasks.

Deliveries:
</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
• source code of your password cracker

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
– Homework Assignment #1 2

</div>
</div>
<div class="layoutArea">
<div class="column">
• a Makefile to build your tool

• a README document to explain your design

• a script to automatically compile, run and print out the result

Problem 2: OpenSSL Server and Client

OpenSSL is a library to provide secure network communication. It also provides many standalone tools to perform encryption/decryption, generate public/private key and certificates. You have exercised OpenSSL api to compute password hash in Problem 1. In this task, you will use OpenSSL tools to establish a secure connection between a server and client , then transfer a file along with its signature, in the end verify the file against its signature.

(a) SSL connection is based on trusted certificates. In this problem, our connection is based on certificates which are created by yourself. Specifically, you need to first create a root certificate, then use it to create and sign an intermediate certificate. Further, you will create and sign a client and server certificates using the intermediate certificates you just created.

(b) Once the certificates are generated, we can establish secure communicate between client and server. You will use OpenSSL tools s server and s client to launch secure SSL connection with the certificates you have created in part (a).

<ul>
<li>On the server side, create a directory named server, enter into the directory. Next, create a file test.txt containing your name and uni. Then generate a signature file test.sign for that file using server’s private key.</li>
<li>On the client side, create a directory named client, enter into the directory. Next, send a simple HTTP request to file test.txt and test.sign. In the end, verify the file against the received signature using OpenSSL tool dgst
Hint:
</li>
</ul>
<ul>
<li>There are many materials online about how to set up self-signed certificates. Here is a nice blog https: //jamielinux.com/docs/openssl-certificate-authority/introduction.html.</li>
<li>Use HTTP request method to obtain files from server. You can directly input HTTP request message inside s client.</li>
<li>The file signature may contain many non-printable characters and is not encoded into some text format like base64. Hence you cannot directly view or examine its content from stdout of s client. Think of IO redirection.
Deliveries:

• two bash scripts to reproduce the each tasks

• the bash scripts should include basic comments

• a README document to explain your design

• a script to automatically run and print out the result
</li>
</ul>
</div>
</div>
</div>
