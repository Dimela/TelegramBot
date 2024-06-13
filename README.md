# TelegramBot
Un pequeño juego de pasos realizado con peticiones en Java Spring boot Maven en Telegram a través de un chatbot.

# Hola soy Dayana
A continuación te dejaré indicaciones para que pruebes el código con tus propias credenciales, ya que las albergadas allí son de mi ejecución.
Paso uno:
- Ingresar a Telegram
- Buscar BotFather
- En la barra para escribir al chat colocar la siguiente palabra y dar Enter: /start
- A continuación, desplegará un menú como este:

I can help you create and manage Telegram bots. If you're new to the Bot API, please see the manual (https://core.telegram.org/bots).
You can control me by sending these commands:

/newbot - create a new bot
/mybots - edit your bots

Edit Bots
/setname - change a bot's name
/setdescription - change bot description
/setabouttext - change bot about info
/setuserpic - change bot profile photo
/setcommands - change the list of commands
/deletebot - delete a bot

Bot Settings
/token - generate authorization token
/revoke - revoke bot access token
/setinline - toggle inline mode (https://core.telegram.org/bots/inline)
/setinlinegeo - toggle inline location requests (https://core.telegram.org/bots/inline#location-based-results)
/setinlinefeedback - change inline feedback (https://core.telegram.org/bots/inline#collecting-feedback) settings
/setjoingroups - can your bot be added to groups?
/setprivacy - toggle privacy mode (https://core.telegram.org/bots/features#privacy-mode) in groups

Web Apps
/myapps - edit your web apps (https://core.telegram.org/bots/webapps)
/newapp - create a new web app (https://core.telegram.org/bots/webapps)
/listapps - get a list of your web apps
/editapp - edit a web app
/deleteapp - delete an existing web app

Games
/mygames - edit your games (https://core.telegram.org/bots/games)
/newgame - create a new game (https://core.telegram.org/bots/games)
/listgames - get a list of your games
/editgame - edit a game
/deletegame - delete an existing game

- Del anterior menú seleccionaremos: /newbot
- Seguido despues del enter en inglés nos pedirá que ingresemos un nombre para el bot, te dejo un ejemplo: developerDR
- después nos indicará que debemos colocar el nombre del bot seguido de guión bajo y palabra bot, te dejo ejemplo: developerDR_bot
- Presentará la siguiente información la cuál deberás reemplazar en el código como el token API, y el enlace de apertura para abrir y probar en telegram:

Done! Congratulations on your new bot. You will find it at t.me/developerDR_bot. You can now add a description, about section and profile picture for your bot, see /help for a list of commands. By the way, when you've finished creating your cool bot, ping our Bot Support if you want a better username for it. Just make sure the bot is fully operational before you do this.

Use this token to access the HTTP API:
# 7073887291:AAG6-CqjbNLp5rBEi1Yll4wrA2kxoPYdPqc
Keep your token secure and store it safely, it can be used by anyone to control your bot.

For a description of the Bot API, see this page: https://core.telegram.org/bots/api

Esto lo aprendí en bootcamp corto, espero les sea de utilidad.
