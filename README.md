# Como remover a hud do samp utilizando um plugin do cef.

Crie a pasta plugins dentro da pasta do cef ( que esta localizado na pasta do gta em que instalou o cef ), e coloque a cef_interface.dll dentro da mesma.

Para remover o hud coloque as seguintes funções no javascript do seu .html.

<code>cef.emit("game:hud:setComponentVisible", "interface", false);</code>
<p>
<code>cef.emit("game:hud:setComponentVisible", "radar", false);</code>
