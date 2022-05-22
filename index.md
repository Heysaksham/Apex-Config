<!DOCTYPE html>
<html lang="en"><head>
  <meta charset="utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>Apex config &amp; tweaks</title><!-- Begin Jekyll SEO tag v2.8.0 -->
<meta name="generator" content="Jekyll v3.9.2" />
<meta property="og:title" content="Apex config &amp; tweaks" />
<meta property="og:locale" content="en_US" />
<link rel="canonical" href="https://deafps.github.io/apex-configs-by-deafps/" />
<meta property="og:url" content="https://deafps.github.io/apex-configs-by-deafps/" />
<meta property="og:site_name" content="apex-configs-by-deafps" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="Apex config &amp; tweaks" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","headline":"Apex config &amp; tweaks","name":"apex-configs-by-deafps","url":"https://deafps.github.io/apex-configs-by-deafps/"}</script>
<!-- End Jekyll SEO tag -->
<link type="application/atom+xml" rel="alternate" href="https://deafps.github.io/apex-configs-by-deafps/feed.xml" title="apex-configs-by-deafps" /><link rel="shortcut icon" type="image/x-icon" href="" />
  <link rel="stylesheet" href="/apex-configs-by-deafps/assets/css/main.css" />
</head><body a="auto">
    <main class="page-content" aria-label="Content">
      <div class="w">
        <header>
  <h1>apex-configs-by-deafps</h1></header><ul></ul><h1 id="apex-config--tweaks">Apex config &amp; tweaks</h1>

<h2 id="launch-options">Launch Options</h2>

<table>
  <thead>
    <tr>
      <th><strong>Command</strong></th>
      <th><strong>Description</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="language-plaintext highlighter-rouge">-dev</code></td>
      <td>Skips EA intro on startup</td>
    </tr>
    <tr>
      <td><code class="language-plaintext highlighter-rouge">+building_cubemaps 1</code></td>
      <td>Removes Top and Bottom Backbars in 4:3 stretched if you alt+enter 2x in continue screen</td>
    </tr>
    <tr>
      <td><code class="language-plaintext highlighter-rouge">+exec</code></td>
      <td>Executes a cfg file on startup</td>
    </tr>
    <tr>
      <td><code class="language-plaintext highlighter-rouge">-window</code></td>
      <td>Starts the game in windowed mode</td>
    </tr>
    <tr>
      <td><code class="language-plaintext highlighter-rouge">-noborder</code></td>
      <td>Removes window border</td>
    </tr>
    <tr>
      <td><code class="language-plaintext highlighter-rouge">+reticle_color R G B</code></td>
      <td>Sets a unrestricted RGB value for the reticle color</td>
    </tr>
  </tbody>
</table>

<h2 id="autoexec">Autoexec</h2>
<ol>
  <li>Go to the games directory. (Usually in C:\Program Files (x86)\Steam\steamapps\common\Apex Legends\cfg)</li>
  <li>Create there a new file called “autoexec.cfg” (without the Quotation marks)</li>
  <li>Paste everything from <a href="https://raw.githubusercontent.com/deaFPS/apex-configs-by-deafps/master/autoexec.cfg">autoexec</a> in it.</li>
  <li>Rightclick on the game inside of Steam and go to “Properties”.</li>
  <li>Add the Launch Option “+exec autoexec.cfg” (without the Quotation marks)</li>
</ol>

<h2 id="videoconfig">Videoconfig</h2>
<ol>
  <li>Press Win+R while you are on your desktop.</li>
  <li>Paste this inside the Run box: “%USERPROFILE%\Saved Games\Respawn\Apex\local” (without the Quotation marks)</li>
  <li>Open up the Videoconfig.txt with Wordpad or Notepad++.</li>
  <li>Replace everything in it with the code from <a href="https://raw.githubusercontent.com/deaFPS/apex-configs-by-deafps/master/videoconfig.txt">videoconfig</a></li>
  <li>Save and make the file read-only.</li>
</ol>

<h2 id="consistant-frame-caping">Consistant frame caping</h2>
<p>Use RTSS for framerate caping over build-in game engines caps. RTSS is the best in frametime consistancy.
Apex Legends and other Soruce Engine games cannot register inputs between frames. The more frames the more often Apex can register inputs.
If your framerate is flactuating your “mouse feeling” will feel off and inconsistent.
You can download RTSS <a href="https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html">here</a></p>

      </div>
    </main>
  </body>
</html>
