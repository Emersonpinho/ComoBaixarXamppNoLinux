
---

# 🐧 Instalando o XAMPP no Linux (Ubuntu)  

> **Observação:** Este tutorial foi testado no Ubuntu, mas pode funcionar em outras distribuições baseadas em Debian.


---

## 📥 1. Baixando o XAMPP  
O XAMPP pode ser baixado diretamente do site oficial:  

🔗 **Acesse:** [https://www.apachefriends.org/download.html](https://www.apachefriends.org/download.html)  



> O arquivo baixado ficará na pasta **"Downloads"** por padrão.  

📸 **Print aqui** ⬇  

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

📸 **Print aqui** ⬇  

---

## 🚀 4. Instalando o XAMPP  
Agora, vamos rodar o instalador:  

```bash
sudo ./xampp-linux-x64-*.run
```  

> O **sudo** é necessário porque estamos instalando um software no sistema.  

📸 **Print aqui** ⬇  

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

---

Pronto! Agora o XAMPP está instalado e funcionando no seu Ubuntu. 🚀🔥
