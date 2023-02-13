# Auto-Palera1n16
Palera1n com todas dependências automaticamente instaladas + iOS16.X iBoot Fix

# Mais Sobre o Auto-Palera1n
Antigo projeto inovador da equipe oficial do jailbreak "Palera1n Gui Linux" desenvolvido para o iOS15.X, agora atualizado pela comunidade do Jailbreak do reddit com total suporte para aparelhos A9, A10 e A11 rodando no iOS16.X, dando fix no famoso erro "iBoot16 Device Detected".
TODOS OS CRÉDITOS RESERVADOS AOS SEUS DEVIDOS DESENVOLVEDORES E EDITORES!

ITALOGC IOS




<h1>Instalação</h1>

<h4>Funciona em qualquer distro linux baseada no <i><strong>Ubuntu 22.04</strong></i> pra cima de preferência <i><strong>Linux mint 21,</strong></i>  20.04 não é suportado!</h4>

<pre>sudo apt install git -y</pre>

<pre>sudo git clone --recursive https://github.com/Italogc/Auto-Palera1n16</pre>

<pre>cd Auto-Palera1n16</pre>

<pre>sudo chmod +x *</pre>

<pre>sudo bash jailbreak SUA_VERSAO_IOS</pre>

<h4>Abra um novo terminal (sem fechar o anterior) e digite:</h4>

<pre>sudo systemctl stop usbmuxd</pre>

<pre>sudo /sbin/usbmuxd -f -p</pre>

<h4>Volte pro terminal anterior aonde você executou o Auto-Palera1n e digite:</h4>

<pre>cd palera1n</pre>

<pre>sudo ./palera1n.sh --tweaks SUA_VERSAO_IOS</pre>


<h4>Caso seu aparelho esteja no iOS15.X e volte para a tela de restauração ao concluir o jailbreak, utilize meu Palera1n-3.0 para fix</h4>

<pre>cd ..</pre>

<pre>cd palera1n-3.0</pre>

<pre>sudo ./palera1n.sh --tweaks SUA_VERSAO_IOS</pre>


<h4>Visite https://github.com/Italogc/palera1n-3.0 para todos detalhes</h4>


<h4>Caso queira remover o Jailbreak</h4>

<pre>cd palera1n</pre>

<pre>sudo ./palera1n.sh --restorerootfs SUA_VERSAO_IOS</pre>


<p>Obrigado!</p>
