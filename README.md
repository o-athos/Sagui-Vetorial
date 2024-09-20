# Processador Vetorial

Essa eh a implementacao de um processador de execucao vetorial, ou seja, uma instrucao age sobre varios dados simultaneamente, por isso ser vetorial.

## Ferramenta

Para a construcao foi usado o simulador Logisim evolution: https://github.com/logisim-evolution/logisim-evolution

## Execucao

Clone este repositorio e tenha o logisim baixado.

Abra o logisim Evolution. Va em "Arquivo" e "Abrir", selecione a pasta do Sagui e o arquivo .circ

Dessa forma, estara a implementacao do procesador. Para carregar um dos codigos selecione com o botao direito o componente "ROM" e selecione "carregar imagem", assim, escolha um dos arquivos .hex para colocar na memoria de instrucao.

Para testar o circuito va em "Simular", depois "Frequencia de Pulso" e escolhe a maior, finalmente, aperte `CTRL + K` para iniciar o pulso no clock.

O codigo e a arquitetura podem ser analisados verificando as memorias RAM's de cada vetor e seus valores sendo alterados.
