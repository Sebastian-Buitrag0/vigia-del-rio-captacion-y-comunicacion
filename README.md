# Vigia Del Rio
Este módulo se encarga de recopilar la información proveniente de los sensores a través de un Arduino MEGA, al cual se conectan 4 sensores de lluvia y un módulo LoRa LR03 como emisor.
Los datos son transmitidos mediante ondas de baja frecuencia hacia un ESP32, que también cuenta con un módulo LoRa LR03 como receptor.
Finalmente, el ESP32 procesa la información recibida y la envía a un servidor MQTT como publicador, facilitando así su distribución a los suscriptores que requieran estos datos.
