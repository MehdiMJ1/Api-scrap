# Api-scrap
<p>apikey search engine scraping methods.</p>
<p>results are displayed based on content</p>
<h2> liked the site </h2>
<ul>
  <li>Github</li>
  <li>Google</li>
  <li>SourceForge</li>
  <li>Oceanofgames</li>
  <li>Happymod</li>
  <li>Uptodown</li>
  <li>Dlandroid</li>
  <li>GameMod</li>
  <li>Rexdl</li>
  <li>A2zapk</li>
</ul>
<strong><h3>start using</h3>
  <h4>Class : Github_search_enggine() - Method : search_github(query) - str<br>
      Class : Sourceforge() - Method : sourceforge(query) -> str <br>
      Class : OceanOfGame() - Method : oceanofgame(query) -> str <br>
      Class : HappyMod() - Method : happymod(query) -> str <br>
      Class : Uptodown() - Method : uptodown(query,lang) -> str <br>
      Class : DlanDroid() - Method : dlandroid(query) -> str <br>
      Class : Gamemod() - Method : gamemod(query) -> str <br>
      Class : A2zapk() - Method : a2zapk(query) -> str <br>
      Class : Rexdl() - Method : rexdl(query) -> str <br>
      Class : Google() - Method : google_search_query(query,lang,maxSearch,kwargs) -> str -> int -> opt <br>
      Class : Warna() - Method : color[value] -> str - red,cyan,magenta,green,blue,yellow <br><h4></strong>
#call the class method<br>from scrap import *<br><br>
#displays results<br><br>
wrna = Warna().color;<br>
print(wrna["red"]+"RED"+wrna["cyan"]+"CYAN");<br>
print(wrna["green"]+"GREEN"+wrna["magenta"]+"MAGENTA");<br>
print(wrna["yellow"]+"YELLOW"+wrna["blue"]+"BLUE");<br>
print(HappyMod().happymod("free fire"));<br>
print(Github_search_enggine().search_github("free fire"));<br>
print(Sourceforge().sourceforge("tools"));<br>
print(OceanOfGame().oceanofgame("free fire"));<br>
print(Uptodown().uptodown("free fire","id"));<br>
print(DlanDroid().dlandroid("free fire"));<br>
print(Gamemod().gamemod("free fire"));<br>
print(A2zapk().a2zapk("free fire"));<br>
print(Rexdl().rexdl("free fire"));<br>
print(Google().google_search_query("free fire",lang="id",maxSearch=10));<br><br>

- classname().methodname(query) -> <a href="https://github.com/ExsoKamabay/Api-scrap/blob/master/example-response.txt">return json</a>
- take a specific <a href="https://github.com/ExsoKamabay/Api-scrap/blob/master/Response-value.text">value</a><br>
classname().methodname(query)["<a href="https://github.com/ExsoKamabay/Api-scrap/blob/master/Response-value.text">value</a>"]<br><br> Mail : lexyong66@gmail.com;

 
