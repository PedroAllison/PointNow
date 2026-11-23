# PointNow ⏱️

App simples de **bater ponto** para Android.

## 📲 Baixar o app
👉 **[Baixar PointNow.apk](https://github.com/PedroAllison/PointNow/releases/latest/download/PointNow.apk)**

Abra o arquivo no celular e permita "Instalar apps de fontes desconhecidas".

## Como funciona
- **ENTRADA** / **SAÍDA**: ao tocar, pergunta *"Confirmar horário atual?"*
  - **Sim** → registra o horário exato.
  - **Não** → abre uma janela para escolher dia e horário.
- O app identifica sozinho se o próximo registro é entrada ou saída (o botão errado fica desativado).
- **Lembretes**: configure horários e a mensagem de cada notificação diária (ex.: 08:00 "Já bateu o ponto de entrada?"). Toque em *Salvar lembretes* e permita as notificações.
- Lista de registros por dia com total de horas trabalhadas. Dados ficam salvos no celular.

## Desenvolvimento
O código do app está em `www/index.html` (Capacitor). A cada push na `main`, o GitHub Actions gera o APK e publica em **Releases**.
