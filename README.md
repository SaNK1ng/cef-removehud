# Como remover a hud do samp utilizando um plugin do cef.

Crie a pasta plugins dentro da pasta do cef, na sua pasta do gta e coloque a cef_interface.dll dentro da mesma.

Para remover o hud coloque as seguintes funções no javascript do seu .html.

cef.emit("game:hud:setComponentVisible", "interface", false);
cef.emit("game:hud:setComponentVisible", "radar", false);
