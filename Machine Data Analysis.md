<p>Die hinterlegte Formel-Engine basiert auf der Bibliothek „mxParser“. Die vollständige Dokumetation des Funktionsumfang findet sich  <a href="http://mathparser.org/mxparser-math-collection/">hier</a>.</p>
<p>Die folgende Zusammenstellung gibt einen überblick über die gängigsten Funktionalitäten:</p>
<h2 id="operatoren">Operatoren</h2>

<table>
<thead>
<tr>
<th><strong>Key Word</strong></th>
<th><strong>Beschreibung</strong></th>
<th><strong>Beispiel</strong></th>
<th><strong>Ergbnis für a = 2 und b = 3</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>+</td>
<td>Addition</td>
<td>a + b</td>
<td>5</td>
</tr>
<tr>
<td>-</td>
<td>Subtraktion</td>
<td>a - b</td>
<td>-1</td>
</tr>
<tr>
<td>*</td>
<td>Multiplikation</td>
<td>a * b</td>
<td>6</td>
</tr>
<tr>
<td>/</td>
<td>Division</td>
<td>a / b</td>
<td>0,667</td>
</tr>
<tr>
<td>^</td>
<td>Potenzierung</td>
<td>a ^ b</td>
<td>8</td>
</tr>
</tbody>
</table><h2 id="binäre-verknüpfungen">Binäre Verknüpfungen</h2>

<table>
<thead>
<tr>
<th><strong>Key Word</strong></th>
<th><strong>Beschreibung</strong></th>
<th><strong>Beispiel</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>=</td>
<td>Gleichheit</td>
<td>a = b</td>
</tr>
<tr>
<td>&lt;&gt;</td>
<td>Ungleichheit</td>
<td>a &lt;&gt; b</td>
</tr>
<tr>
<td>&lt;</td>
<td>kleiner als</td>
<td>a &lt; b</td>
</tr>
<tr>
<td>&gt;</td>
<td>größer als</td>
<td>a &gt; b</td>
</tr>
<tr>
<td>&lt;=</td>
<td>kleiner oder gleich</td>
<td>a &lt;= b</td>
</tr>
<tr>
<td>&gt;=</td>
<td>größer oder gleich</td>
<td>a &gt;= b</td>
</tr>
</tbody>
</table><h2 id="boolsche-operatoren">Boolsche Operatoren</h2>

<table>
<thead>
<tr>
<th><strong>Key Word</strong></th>
<th><strong>Beschreibung</strong></th>
<th><strong>Beispiel</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>&amp;</td>
<td>und</td>
<td>(a&gt;2) &amp; (b&lt;5)</td>
</tr>
<tr>
<td>|</td>
<td>oder</td>
<td>(a&gt;2) | (b&lt;5)</td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table><h2 id="trigonometrische-und-logarithmische-funktion">Trigonometrische und logarithmische Funktion</h2>

<table>
<thead>
<tr>
<th><strong>Key Word</strong></th>
<th><strong>Beschreibung</strong></th>
<th><strong>Beispiel</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>sin</td>
<td>Sinus-Funktion</td>
<td>sin(a)</td>
</tr>
<tr>
<td>ln</td>
<td>Logarithmusfunktion zur Basis e</td>
<td>ln(a)</td>
</tr>
<tr>
<td>log2</td>
<td>Logarithmusfunktion zur Basis 2</td>
<td>log2(a)</td>
</tr>
<tr>
<td>log10</td>
<td>Logarithmusfunktion zur Basis 10</td>
<td>log10(a)</td>
</tr>
<tr>
<td>exp</td>
<td>Exponentialfunktion</td>
<td>exp(a)</td>
</tr>
<tr>
<td>sqrt</td>
<td>Wurzelfunktion</td>
<td>sqrt(a)</td>
</tr>
</tbody>
</table><p>Analog stehen cos, tan, cot, asin, arcsin, sinh, acos, arccos und weitere Funktionen zur Verfügung.</p>
<h2 id="sonstige-funktionen">sonstige Funktionen</h2>

<table>
<thead>
<tr>
<th><strong>Key Word</strong></th>
<th><strong>Beschreibung</strong></th>
<th><strong>Beispiel</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>if</td>
<td>Wenn-Dann-Abfrage( if(con, if_true, if_false) )</td>
<td>if(a=1,2,0)</td>
</tr>
<tr>
<td>min</td>
<td>Minimum einer Auswahl: min(a,b,c,…)</td>
<td>min(a,b)</td>
</tr>
<tr>
<td>max</td>
<td>Maximum einer Auswahl: max(a,b,c,…)</td>
<td>max(a,b)</td>
</tr>
<tr>
<td>mean</td>
<td>Mittelwert einer Auswahl: mean(abc…)</td>
<td>mean(a,b)</td>
</tr>
<tr>
<td>floor</td>
<td>Abrunden</td>
<td>floor(a)</td>
</tr>
</tbody>
</table><h2 id="konstanten">Konstanten</h2>

<table>
<thead>
<tr>
<th><strong>Key Word</strong></th>
<th><strong>Beschreibung</strong></th>
<th><strong>Beispiel</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>pi</td>
<td>PI=3.14159265359</td>
<td>2 * pi</td>
</tr>
<tr>
<td>e</td>
<td>Euler-Zahl = 2.71828182846</td>
<td>3 * e</td>
</tr>
</tbody>
</table>
