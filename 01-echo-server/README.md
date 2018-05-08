# How to start

(1) build image

<code>
  $ docker build -t echo-server .
</code>

(2) run image

<code>
  $ docker run -it --rm -p 4000:18888 echo-server
</code>

if you get the log like below:

`2018/05/08 16:24:58 start http listening :18888`

you will be able to access `localhost:4000`