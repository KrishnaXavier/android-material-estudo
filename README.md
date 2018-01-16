# Material para estudo de Android (dispositivo móveis)

<ul>
  <a href="#intro"><li>Conceitos iniciais.</li></a>
  <li>Plataforma e ambiente de desenvolvimento.</li>
  <li>Manifest, Activity, Intent, Service</li>
  <li>Layout (gerenciamento de interface e View)</li>
  <li>Recursos:
    <ul>
        <li>BroadcastReceiver</li>      
        <li>Notification</li>
        <li>HTTPConnect</li>
        <li>AlarmManager</li>
        <li>Handler</li>
        <li>Câmera</li>
        <li>GPS</li>
        <li>Mapas</li>
        <li>SMS</li>
        <li>Áudio</li>
        <li>Content Provider</li>
        <li>Entrada e Saída</li>      
     </ul>
   </li>
  <li>Banco de Dados SQLite</li>
  <li>Aplicações Hibridas</li>
</ul>

<div id="intro">
# Introdução
<div>Este material tem como foco os conceitos teoricos básico de Android. O material tem como base a 
<a href="https://developer.android.com/index.html?hl=pt-br"  target="_blank"> documentação oficial</a>.
</div>
<p>
<div>Para quem tem interesse em conhecer a plataforma de desenvolvimento oficial do Android pode instalar o <a href="https://developer.android.com/studio/index.html?hl=pt-br" target="_blank"> Android Studio</a>, a instalação pode demorar algumas horas e vai ocupar alguns gigas em seus HD.</div>

## O que é o Android?
Android é uma plataforma de desenvolvimento aberta voltada para dispositivos móveis criada pela Google. Todas as aplicações desenvolvidas para essa plataforma foram criadas com a linguagem Java. 
<p>
A primeira versão do Android que foi divulgada em 5 de novembro de 2007. Inicialmente o sistema Android foi desenvolvido pelo
Google e atualmente essa plataforma é mantida pela OHA (<a href="http://www.openhandsetalliance.com">Open Handset Alliance</a>), um grupo constituído por aproximadamente 84 empresas as quais se uniram para inovar e acelerar o desenvolvimento de aplicações e serviços, com o objetivo e trazer aos consumidores uma experiência mais rica em termos de recursos, menos dispendiosa em ternos financeiros para o mercado móvel.
 
## O que é o SDK (software development kit)?
O Android SDK é uma ferramenta de desenvolvimento que disponibiliza um conjunto de APIs necessárias para desenvolver aplicações para a plataforma Android, utilizando a linguagem Java. A SDK apresentar varios recursos, veja alguns:
<ul>
  <li>Dalvik virtual machine: É uma Máquina Virtual Java (JVM) voltada para dispositivos móveis.</li>
  <li>Browser Integrado.</li>
  <li>Gráficos Otimizados O Android é constituído por bibliotecas 2D e 3D baseada na especificação OpenGL ES 1.0.</li>
  <li>SQLite: Sistema Gerenciador de Banco de Dados (SGBD) já embutido no Android para guardar dados.</li>
  <li>Suporte multimídia: A plataforma já oferece para áudio, vídeo e formatos de imagem (MPEG4, H.264, MP3, AAC, AMR, JPG, PNG, GIF).</li>
  <li>Câmera, GPS, compasso, e acelerômetro (dependente de hardware).</li>
  <li>Bluetooth, EDGE, 3G, e WiFi (dependente de hardware).</li>
  <li>Rico ambiente de desenvolvimento , incluindo um emulador de dispositivo,ferramentas de depuração, memória e performance.</li>
</ul>

## O que o Linux tem haver com Android?
O Android foi projetado em cima da versão 2.6 do kernel do Linux para os serviços centrais do sistema, tais como segurança, gestão de memória, gestão de processos, etc. O kernel também atua como uma camada de abstração entre o hardware e o resto do software.

## Historia do Android Studio.
Há algum tempo atrás a ferramenta de desenvolvimento Eclipse com o plugin ADT focado para o desenvolvimento Android (junto com o Android SDK), deixou de ser a ferramenta de desenvolvimento oficial para Android.
<p>
Agora o Google adotou como ferramenta oficial de desenvolvimento o Android Studio (baseada e inspirada na ferramenta IntelliJ IDEA) , onde podemos desenvolver nossas aplicações para Android utilizando a linguagem de programação Java.
  
## Versões do Android.
Android 1.0

Android 1.5 Cupcake

Android 1.6 Donut

Android 2.0 Eclair

Android 2.3 Gingerbread

Android 3.0 Honeycomb

Android 4.0 Ice Cream Sandwich

Android 4.1 Jelly Bean

Android 4.4 Kitkat

Android 5.0 Lollipop

Android 6.0 Marshmallow

Android 7.0 Nougat

Android 8.0 Oreo
</div>
