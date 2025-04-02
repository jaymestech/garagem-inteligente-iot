# 🚗 Garagem Inteligente IoT  

Este projeto é uma **garagem inteligente** que usa **Arduino/ESP8266**, enviando dados para o **ThingSpeak**.  

## 📌 Funcionalidades  
- Abre e fecha o portão automaticamente via sensor.  
- Monitora o status do portão (Aberto/Fechado) no ThingSpeak.  
- Conta o número de vezes que o portão foi acionado.  

## 🛠️ Componentes Utilizados  
- **Placa de controle:** ESP8266 ou Arduino  
- **Sensores:** Sensor ultrassônico (HC-SR04)
- **Atuadores:** Servo motor para abrir o portão  
- **Comunicação:** Wi-Fi para enviar os dados ao ThingSpeak  

## 🔗 Links Importantes  
- [Repositório no GitHub](https://github.com/SEU_USUARIO/garagem-inteligente-iot)  
- [Canal do ThingSpeak](https://thingspeak.com/channels/SEU_CANAL_ID)  

## 📷 Imagens  

![Circuito](./imagens/circuito.png)  

---

### **3️⃣ Subindo os Arquivos para o Repositório**  
Agora, faça o **commit** e envie os arquivos:  

```sh
git add .
git commit -m "Adicionando código e documentação do projeto"
git push origin main
