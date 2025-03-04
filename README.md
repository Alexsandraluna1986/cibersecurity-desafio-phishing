# Phishing para captura de senhas do Facebook

### Ferramentas Utilizadas
- **Kali Linux**
- **Setoolkit**

### Configuração do Phishing no Kali Linux

1. **Acesso Root**  
   Para obter permissões de administrador, execute o comando:  
   ```bash
   sudo su
   ```

2. **Iniciando o Setoolkit**  
   Inicie o Setoolkit com o comando:  
   ```bash
   setoolkit
   ```

3. **Seleção do Tipo de Ataque**  
   Escolha a opção:  
   ```
   Social-Engineering Attacks
   ```

4. **Definição do Vetor de Ataque**  
   Selecione:  
   ```
   Web Site Attack Vectors
   ```

5. **Escolha do Método de Ataque**  
   Utilize o método:  
   ```
   Credential Harvester Attack Method
   ```  
   Em seguida, selecione:  
   ```
   Site Cloner
   ```

6. **Obtenção do Endereço IP da Máquina**  
   Para obter o endereço IP da máquina, execute:  
   ```bash
   ifconfig
   ```

7. **Inserção da URL para Clonagem**  
   Insira a URL do site que deseja clonar, por exemplo:  
   ```
   http://www.facebook.com
   ```

### Resultados
Após a configuração, os dados capturados serão exibidos no terminal. Certifique-se de monitorar os resultados para coletar as credenciais.

![Alt text](./passwd.png "Optional title")
