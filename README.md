# backendPF
Descargar la carpeta madre backend, abrirla en Visual studio code, entrar app.js, abrir la terminal y ejecutar los comandos cd backendPF, luego ejecutar node app.js y ya estaría corriendo el servidor en el localhost 3000. Luego abrimos login.html en la carpeta del frontend y con live server o go live iniciamos sesión con el usuario estudiante y la contraseña 123456. 

Token: Para ver el token generado para el usuario, abrir postman, realizar una solicitud POST: http://localhost:3000/login con el body seleccionar la opción raw y detallar: 
{
    "username": "estudiante",
    "password": "123456"
}
Por último, nos imprime en body tipo JSON el token: 


{
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImVzdHVkaWFudGUiLCJpYXQiOjE3MzI5MTg3NDUsImV4cCI6MTczMjkxODc3NX0.uYqvn_vPq-gR8z_rnL-GswSWomvWkS7XwevtCfbZYSY"
}





