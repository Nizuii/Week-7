# 🪱 What is a computer worm?
<ul>
  <li>A worm is a standalone malicious program that replicates itself to spread automatically to other computers.</li>
  <li>Unlike virus worm doesnt need a host file or human execution to spread. They exploit security vulnerabilities, software weakness or network protocols to gain access to sustems and create copies of themselves.</li>
  <li>Once a worm infects a computer, it can use that system to scan and infect other devices.</li>
</ul>

<h2>How a worms gets in?</h2>
<ul>
  <li><strong>Through Vulnerabilities:</strong> If a system or software has a security flaw, a worm can sneak in automatically by eploiting that weakness.</li>
  <strong>Example:</strong> A worm scanss the internet for specific unpatched ports open. Then injects itself.
  <li><strong>Through Emails or Links:</strong> Some worms disguise themselves as attachments or links. When you open them, They execute their code and starts spreading inside your network.</li>
  <strong>Example:</strong> "ILOVEYOU" worm came as an email attachment. People opened it with curiosity and boom. It infected millions of systems accross the world.
  <li><strong>Through network sharing:</strong> If a system connected to a network. A worm can jump from one system to another through shared folders or network vulnerabilities.</li>
  <strong></strong>
</ul>

<h2>How worm spreads through a network.</h2>
<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/24b796ee-a6b6-4ce5-846d-9dc5aec0dd26.png"> 
<ol>
  <li><strong>Initial infection:</strong> The worm infects one vulnerable system on a network through a method like email attachment, malicious link, network vulnerability or infected removable device.</li>
  <li><strong>Activation:</strong> The worm activaes itself on a infected computer without the user's knowledge.</li>
  <li><strong>Scanning and Propogation:</strong> The infected computer scans the network for other vulnerable systems by exploiting securty weakness or software flaws.</li>
  <li><strong>Replication:</strong> Once a vulnerable system is found the worm sends a copy of itself to that system and infects it.</li>
  <li><strong>Spread outward:</strong> Each newly infected system repeats the scanning and replication quickly, spreading the worm acrossing the network.</li>
  <li><strong>Network effects:</strong> This exponential spread continues, consuming bandwitch and resources, slowing down or crashing the systems on the network.</li>
  <li><strong>Payload execution (Optional):</strong> Depending on the worm it may execute payload to steal the data, installing backdoor or launching attack on the systems.</li>
</ol>
