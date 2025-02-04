
---

# 🐧 Instalando o XAMPP no Linux (Ubuntu)  

> **Observação:** Este tutorial foi testado no Ubuntu, mas pode funcionar em outras distribuições baseadas em Debian.


---

## 📥 1. Baixando o XAMPP  
O XAMPP pode ser baixado diretamente do site oficial:  

🔗 **Acesse:** [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)  

📸 **Print aqui** ⬇  

<div style="width: 300px; height: 300px; border: 2px solid #000; display: flex; justify-content: center; align-items: center;">
    <img src="https://github.com/Emersonpinho/ComoBaixarXamppNoLinux/blob/main/img/Captura%20de%20tela%20de%202025-02-04%2015-04-04.png" alt="Descrição da imagem" style="max-width: 100%; max-height: 100%;">
</div> 

📸 **Print aqui** ⬇  

<div style="width: 300px; height: 300px; border: 2px solid #000; display: flex; justify-content: center; align-items: center;">
    <img src="https://github.com/Emersonpinho/ComoBaixarXamppNoLinux/blob/main/img/WhatsApp%20Image%202025-02-04%20at%203.13.03%20PM.jpeg" alt="Descrição da imagem" style="max-width: 100%; max-height: 100%;">
</div>

> O arquivo baixado ficará na pasta **"Downloads"** por padrão. 

---

## 💻 2. Abrindo o Terminal  
Para instalar o XAMPP, precisamos abrir o **Terminal**. Existem algumas maneiras:  

1️⃣ Pressione `Ctrl + Alt + T` para abrir rapidamente.  
2️⃣ Ou pesquise por **Terminal** no menu de aplicativos e abra.  

📸 **Print aqui** ⬇  

---

## 🔓 3. Tornando o Arquivo Executável  
O arquivo baixado precisa de permissão para ser executado. Vamos dar essa permissão:  

1️⃣ Acesse a pasta onde está o arquivo:  
```bash
cd ~/Downloads
```  
2️⃣ Torne o arquivo **executável** com o comando:  
```bash
chmod +x xampp-linux-x64-*.run
```   

---

## 🚀 4. Instalando o XAMPP  
Agora, vamos rodar o instalador:  

```bash
sudo ./xampp-linux-x64-*.run
```  

> O **sudo** é necessário porque estamos instalando um software no sistema.  


---

## ✅ 5. Verificando se o XAMPP Está Funcionando  
Depois da instalação, podemos iniciar o XAMPP com:  

```bash
sudo /opt/lampp/lampp start
```  

Agora, abra o navegador e acesse:  

🔗 **http://localhost**  

Se aparecer a página do XAMPP, está tudo certo! 🎉  

📸 **Print aqui** ⬇  
<div style="width: 300px; height: 300px; border: 2px solid #000; display: flex; justify-content: center; align-items: center;">
    <img src="https://github.com/Emersonpinho/ComoBaixarXamppNoLinux/blob/main/img/Captura%20de%20tela%20de%202025-02-04%2015-18-47.png" alt="Descrição da imagem" style="max-width: 100%; max-height: 100%;">
</div>

---

Pronto! Agora o XAMPP está instalado e funcionando no seu Ubuntu. 🚀🔥
