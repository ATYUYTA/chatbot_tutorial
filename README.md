
--------------------------------------------------
#git the repo
>git clone https://github.com/ATYUYTA/chatbot_tutorial.git

>cd chatbot_tutorial

#build the environment
>docker-compose up --build -d

#API jupyter
http://127.0.0.1:8880

#Line api jupyter
http://127.0.0.1:8888

以下為資料夾結構

#主要是跟API跟SQL有關
Chatbot_Dev/
>
裝有api的程式碼
>code/
裝初始化資料庫的檔案
>mysql_init/
>

#主要是裝有關於Line API，redis跟ngrok有關的資料
Chatbot_Line/
>
裡面都是跟Line API 有關的程式碼
>code
裝有redis的資料
>redis/data/

#裡面裝各個image的客制化訊息
dockerfile/

#利用docker-compose一次開啟五個container
docker-compose.yml
