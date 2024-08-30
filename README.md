## **Cobrar**
### 1. [**APIs**](#apis)
### 2. [**Banco de Dados**](#banco-de-dados)
### 3. [**Linux**](#linux)


# **APIs**
Aqui vai ficar algumas informações de IP e PORTA e qual API está sendo executada,

- 192.168.1.93 - Servidor de Aplicação
    - IIS
        -   Nome API    | PORTA |   IP BANCO   | BASE 
        -   ApiSrc360   | 8090  | 192.168.1.16 | SRC 
        - ProcessTasken | 8080  | 192.168.1.16 | SRC

    - IIS 
        - ApiSrc360
            <details>
                <summary>URL</summary>

                ```
                http://192.168.1.93:8090/
                ```
            </details>
            <details>
                <summary>Banco</summary>

                ```
                192.168.1.16
                ```
            </details>
            <details>
                <summary>Base</summary>

                ```
                SRC
                ```
            </details>

        - ProcessTasken
            <details>
                <summary>URL</summary>

                ```
                http://192.168.1.93:8080/
                ```
            </details>
            <details>
                <summary>Banco</summary>

                ```
                192.168.1.16
                ```
            </details>
            <details>
                <summary>Base</summary>
                
                ```
                SRC
                ```
            </details>

    - Serviços Windows
        -   Nome Serviço        |   IP BANCO
        - Tasken Process Scheduler | 192.168.1.16

# **Banco de Dados**
- 192.168.1.16 - Banco de Dados

# **Linux**
- 192.168.1.93 - Aplicação
    - Docker 
        - srcwebdashboard | 9000
        - autonegociadordashboard | 8081
        - analyticsapi
        - srcwebapi | 3000
        - acionamento
        - autonegociadorapi
        - acordosalterados
        - promessa
        - licencas2.0-api | 84
