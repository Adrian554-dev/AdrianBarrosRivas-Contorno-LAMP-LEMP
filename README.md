# AdrianBarrosRivas-Contorno-LAMP-LEMP

# 📦 Proxecto de Entornos de Desenvolvemento LAMP e LEMP  

Este proxecto inclúe dous entornos de desenvolvemento completamente funcionais: **LAMP** e **LEMP**. Ambos permiten a instalación en desarrollo de Prestashop.  

## Instalación e Execución  

1. **Descargar e descomprimir** o ficheiro ZIP do proxecto.  
2. Para levantar o entorno desexado, executar o comando correspondente:  

   - **LAMP**:  
     ```bash
     docker compose -f compose-lamp.dev.yml up --build
     ```  
   - **LEMP**:  
     ```bash
     docker compose -f compose-lemp.dev.yml up --build
     ```  

3. Unha vez iniciado o contorno, introducir os datos de conexión coa base de datos utilizando as credenciais definidas no ficheiro `.env` entregado na aula virtual.  



