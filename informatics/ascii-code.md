---
title: ASCIIコード一覧
tags: [info-1]
---

<style>
    table {
        margin: 0 auto;
        border-collapse: collapse;
    }
    th, td {
        border: 1px solid #ddd;
        padding: 8px;
    }
    th.dec,
    td.dec {
        text-align: right;
        width: 4em;
    }
    th.bin,
    td.bin {
        text-align: right;
        width: 8em;
    }
    th.hex,
    td.hex {
        text-align: right;
        width: 4em;
    }
    th.ascii,
    td.ascii {
        text-align: center;
        width: 8em;
        font-weight: bold;
    }
    th.dec,
    th.bin,
    th.hex,
    th.ascii {
        text-align: center;
        background-color: #e9e9e9;
    }
    .control {
        color: orange;
    }
    tr:nth-child(odd) {
        background-color: #f9f9f9;
    }
</style>

<table>
    <tr><th class="dec">10進</th><th class="bin">2進</th><th class="hex">16進</th><th class="ascii">ASCII</th></tr>
    <tr><td class="dec">0</td><td class="bin">0</td><td class="hex">0</td><td class="ascii control">NULL</td></tr>
    <tr><td class="dec">1</td><td class="bin">1</td><td class="hex">1</td><td class="ascii control">SOH</td></tr>
    <tr><td class="dec">2</td><td class="bin">10</td><td class="hex">2</td><td class="ascii control">STX</td></tr>
    <tr><td class="dec">3</td><td class="bin">11</td><td class="hex">3</td><td class="ascii control">ETX</td></tr>
    <tr><td class="dec">4</td><td class="bin">100</td><td class="hex">4</td><td class="ascii control">EOT</td></tr>
    <tr><td class="dec">5</td><td class="bin">101</td><td class="hex">5</td><td class="ascii control">ENG</td></tr>
    <tr><td class="dec">6</td><td class="bin">110</td><td class="hex">6</td><td class="ascii control">ACK</td></tr>
    <tr><td class="dec">7</td><td class="bin">111</td><td class="hex">7</td><td class="ascii control">BEL</td></tr>
    <tr><td class="dec">8</td><td class="bin">1000</td><td class="hex">8</td><td class="ascii control">BS</td></tr>
    <tr><td class="dec">9</td><td class="bin">1001</td><td class="hex">9</td><td class="ascii control">HT</td></tr>
    <tr><td class="dec">10</td><td class="bin">1010</td><td class="hex">A</td><td class="ascii control">LF</td></tr>
    <tr><td class="dec">11</td><td class="bin">1011</td><td class="hex">B</td><td class="ascii control">VT</td></tr>
    <tr><td class="dec">12</td><td class="bin">1100</td><td class="hex">C</td><td class="ascii control">FF</td></tr>
    <tr><td class="dec">13</td><td class="bin">1101</td><td class="hex">D</td><td class="ascii control">CR</td></tr>
    <tr><td class="dec">14</td><td class="bin">1110</td><td class="hex">E</td><td class="ascii control">SO</td></tr>
    <tr><td class="dec">15</td><td class="bin">1111</td><td class="hex">F</td><td class="ascii control">SI</td></tr>
    <tr><td class="dec">16</td><td class="bin">10000</td><td class="hex">10</td><td class="ascii control">DLE</td></tr>
    <tr><td class="dec">17</td><td class="bin">10001</td><td class="hex">11</td><td class="ascii control">DC1</td></tr>
    <tr><td class="dec">18</td><td class="bin">10010</td><td class="hex">12</td><td class="ascii control">DC2</td></tr>
    <tr><td class="dec">19</td><td class="bin">10011</td><td class="hex">13</td><td class="ascii control">DC3</td></tr>
    <tr><td class="dec">20</td><td class="bin">10100</td><td class="hex">14</td><td class="ascii control">DC4</td></tr>
    <tr><td class="dec">21</td><td class="bin">10101</td><td class="hex">15</td><td class="ascii control">NAK</td></tr>
    <tr><td class="dec">22</td><td class="bin">10110</td><td class="hex">16</td><td class="ascii control">SYN</td></tr>
    <tr><td class="dec">23</td><td class="bin">10111</td><td class="hex">17</td><td class="ascii control">ETB</td></tr>
    <tr><td class="dec">24</td><td class="bin">11000</td><td class="hex">18</td><td class="ascii control">CAN</td></tr>
    <tr><td class="dec">25</td><td class="bin">11001</td><td class="hex">19</td><td class="ascii control">EM</td></tr>
    <tr><td class="dec">26</td><td class="bin">11010</td><td class="hex">1A</td><td class="ascii control">SUB</td></tr>
    <tr><td class="dec">27</td><td class="bin">11011</td><td class="hex">1B</td><td class="ascii control">ESC</td></tr>
    <tr><td class="dec">28</td><td class="bin">11100</td><td class="hex">1C</td><td class="ascii control">FS</td></tr>
    <tr><td class="dec">29</td><td class="bin">11101</td><td class="hex">1D</td><td class="ascii control">GS</td></tr>
    <tr><td class="dec">30</td><td class="bin">11110</td><td class="hex">1E</td><td class="ascii control">RS</td></tr>
    <tr><td class="dec">31</td><td class="bin">11111</td><td class="hex">1F</td><td class="ascii control">US</td></tr>
    <tr><td class="dec">32</td><td class="bin">100000</td><td class="hex">20</td><td class="ascii">SP</td></tr>
    <tr><td class="dec">33</td><td class="bin">100001</td><td class="hex">21</td><td class="ascii">!</td></tr>
    <tr><td class="dec">34</td><td class="bin">100010</td><td class="hex">22</td><td class="ascii">"</td></tr>
    <tr><td class="dec">35</td><td class="bin">100011</td><td class="hex">23</td><td class="ascii">#</td></tr>
    <tr><td class="dec">36</td><td class="bin">100100</td><td class="hex">24</td><td class="ascii">$</td></tr>
    <tr><td class="dec">37</td><td class="bin">100101</td><td class="hex">25</td><td class="ascii">%</td></tr>
    <tr><td class="dec">38</td><td class="bin">100110</td><td class="hex">26</td><td class="ascii">&</td></tr>
    <tr><td class="dec">39</td><td class="bin">100111</td><td class="hex">27</td><td class="ascii">'</td></tr>
    <tr><td class="dec">40</td><td class="bin">101000</td><td class="hex">28</td><td class="ascii">(</td></tr>
    <tr><td class="dec">41</td><td class="bin">101001</td><td class="hex">29</td><td class="ascii">)</td></tr>
    <tr><td class="dec">42</td><td class="bin">101010</td><td class="hex">2A</td><td class="ascii">*</td></tr>
    <tr><td class="dec">43</td><td class="bin">101011</td><td class="hex">2B</td><td class="ascii">+</td></tr>
    <tr><td class="dec">44</td><td class="bin">101100</td><td class="hex">2C</td><td class="ascii">,</td></tr>
    <tr><td class="dec">45</td><td class="bin">101101</td><td class="hex">2D</td><td class="ascii">-</td></tr>
    <tr><td class="dec">46</td><td class="bin">101110</td><td class="hex">2E</td><td class="ascii">.</td></tr>
    <tr><td class="dec">47</td><td class="bin">101111</td><td class="hex">2F</td><td class="ascii">/</td></tr>
    <tr><td class="dec">48</td><td class="bin">110000</td><td class="hex">30</td><td class="ascii">0</td></tr>
    <tr><td class="dec">49</td><td class="bin">110001</td><td class="hex">31</td><td class="ascii">1</td></tr>
    <tr><td class="dec">50</td><td class="bin">110010</td><td class="hex">32</td><td class="ascii">2</td></tr>
    <tr><td class="dec">51</td><td class="bin">110011</td><td class="hex">33</td><td class="ascii">3</td></tr>
    <tr><td class="dec">52</td><td class="bin">110100</td><td class="hex">34</td><td class="ascii">4</td></tr>
    <tr><td class="dec">53</td><td class="bin">110101</td><td class="hex">35</td><td class="ascii">5</td></tr>
    <tr><td class="dec">54</td><td class="bin">110110</td><td class="hex">36</td><td class="ascii">6</td></tr>
    <tr><td class="dec">55</td><td class="bin">110111</td><td class="hex">37</td><td class="ascii">7</td></tr>
    <tr><td class="dec">56</td><td class="bin">111000</td><td class="hex">38</td><td class="ascii">8</td></tr>
    <tr><td class="dec">57</td><td class="bin">111001</td><td class="hex">39</td><td class="ascii">9</td></tr>
    <tr><td class="dec">58</td><td class="bin">111010</td><td class="hex">3A</td><td class="ascii">:</td></tr>
    <tr><td class="dec">59</td><td class="bin">111011</td><td class="hex">3B</td><td class="ascii">;</td></tr>
    <tr><td class="dec">60</td><td class="bin">111100</td><td class="hex">3C</td><td class="ascii"><</td></tr>
    <tr><td class="dec">61</td><td class="bin">111101</td><td class="hex">3D</td><td class="ascii">=</td></tr>
    <tr><td class="dec">62</td><td class="bin">111110</td><td class="hex">3E</td><td class="ascii">></td></tr>
    <tr><td class="dec">63</td><td class="bin">111111</td><td class="hex">3F</td><td class="ascii">?</td></tr>
    <tr><td class="dec">64</td><td class="bin">1000000</td><td class="hex">40</td><td class="ascii">@</td></tr>
    <tr><td class="dec">65</td><td class="bin">1000001</td><td class="hex">41</td><td class="ascii">A</td></tr>
    <tr><td class="dec">66</td><td class="bin">1000010</td><td class="hex">42</td><td class="ascii">B</td></tr>
    <tr><td class="dec">67</td><td class="bin">1000011</td><td class="hex">43</td><td class="ascii">C</td></tr>
    <tr><td class="dec">68</td><td class="bin">1000100</td><td class="hex">44</td><td class="ascii">D</td></tr>
    <tr><td class="dec">69</td><td class="bin">1000101</td><td class="hex">45</td><td class="ascii">E</td></tr>
    <tr><td class="dec">70</td><td class="bin">1000110</td><td class="hex">46</td><td class="ascii">F</td></tr>
    <tr><td class="dec">71</td><td class="bin">1000111</td><td class="hex">47</td><td class="ascii">G</td></tr>
    <tr><td class="dec">72</td><td class="bin">1001000</td><td class="hex">48</td><td class="ascii">H</td></tr>
    <tr><td class="dec">73</td><td class="bin">1001001</td><td class="hex">49</td><td class="ascii">I</td></tr>
    <tr><td class="dec">74</td><td class="bin">1001010</td><td class="hex">4A</td><td class="ascii">J</td></tr>
    <tr><td class="dec">75</td><td class="bin">1001011</td><td class="hex">4B</td><td class="ascii">K</td></tr>
    <tr><td class="dec">76</td><td class="bin">1001100</td><td class="hex">4C</td><td class="ascii">L</td></tr>
    <tr><td class="dec">77</td><td class="bin">1001101</td><td class="hex">4D</td><td class="ascii">M</td></tr>
    <tr><td class="dec">78</td><td class="bin">1001110</td><td class="hex">4E</td><td class="ascii">N</td></tr>
    <tr><td class="dec">79</td><td class="bin">1001111</td><td class="hex">4F</td><td class="ascii">O</td></tr>
    <tr><td class="dec">80</td><td class="bin">1010000</td><td class="hex">50</td><td class="ascii">P</td></tr>
    <tr><td class="dec">81</td><td class="bin">1010001</td><td class="hex">51</td><td class="ascii">Q</td></tr>
    <tr><td class="dec">82</td><td class="bin">1010010</td><td class="hex">52</td><td class="ascii">R</td></tr>
    <tr><td class="dec">83</td><td class="bin">1010011</td><td class="hex">53</td><td class="ascii">S</td></tr>
    <tr><td class="dec">84</td><td class="bin">1010100</td><td class="hex">54</td><td class="ascii">T</td></tr>
    <tr><td class="dec">85</td><td class="bin">1010101</td><td class="hex">55</td><td class="ascii">U</td></tr>
    <tr><td class="dec">86</td><td class="bin">1010110</td><td class="hex">56</td><td class="ascii">V</td></tr>
    <tr><td class="dec">87</td><td class="bin">1010111</td><td class="hex">57</td><td class="ascii">W</td></tr>
    <tr><td class="dec">88</td><td class="bin">1011000</td><td class="hex">58</td><td class="ascii">X</td></tr>
    <tr><td class="dec">89</td><td class="bin">1011001</td><td class="hex">59</td><td class="ascii">Y</td></tr>
    <tr><td class="dec">90</td><td class="bin">1011010</td><td class="hex">5A</td><td class="ascii">Z</td></tr>
    <tr><td class="dec">91</td><td class="bin">1011011</td><td class="hex">5B</td><td class="ascii">[</td></tr>
    <tr><td class="dec">92</td><td class="bin">1011100</td><td class="hex">5C</td><td class="ascii">\</td></tr>
    <tr><td class="dec">93</td><td class="bin">1011101</td><td class="hex">5D</td><td class="ascii">]</td></tr>
    <tr><td class="dec">94</td><td class="bin">1011110</td><td class="hex">5E</td><td class="ascii">^</td></tr>
    <tr><td class="dec">95</td><td class="bin">1011111</td><td class="hex">5F</td><td class="ascii">_</td></tr>
    <tr><td class="dec">96</td><td class="bin">1100000</td><td class="hex">60</td><td class="ascii">`</td></tr>
    <tr><td class="dec">97</td><td class="bin">1100001</td><td class="hex">61</td><td class="ascii">a</td></tr>
    <tr><td class="dec">98</td><td class="bin">1100010</td><td class="hex">62</td><td class="ascii">b</td></tr>
    <tr><td class="dec">99</td><td class="bin">1100011</td><td class="hex">63</td><td class="ascii">c</td></tr>
    <tr><td class="dec">100</td><td class="bin">1100100</td><td class="hex">64</td><td class="ascii">d</td></tr>
    <tr><td class="dec">101</td><td class="bin">1100101</td><td class="hex">65</td><td class="ascii">e</td></tr>
    <tr><td class="dec">102</td><td class="bin">1100110</td><td class="hex">66</td><td class="ascii">f</td></tr>
    <tr><td class="dec">103</td><td class="bin">1100111</td><td class="hex">67</td><td class="ascii">g</td></tr>
    <tr><td class="dec">104</td><td class="bin">1101000</td><td class="hex">68</td><td class="ascii">h</td></tr>
    <tr><td class="dec">105</td><td class="bin">1101001</td><td class="hex">69</td><td class="ascii">i</td></tr>
    <tr><td class="dec">106</td><td class="bin">1101010</td><td class="hex">6A</td><td class="ascii">j</td></tr>
    <tr><td class="dec">107</td><td class="bin">1101011</td><td class="hex">6B</td><td class="ascii">k</td></tr>
    <tr><td class="dec">108</td><td class="bin">1101100</td><td class="hex">6C</td><td class="ascii">l</td></tr>
    <tr><td class="dec">109</td><td class="bin">1101101</td><td class="hex">6D</td><td class="ascii">m</td></tr>
    <tr><td class="dec">110</td><td class="bin">1101110</td><td class="hex">6E</td><td class="ascii">n</td></tr>
    <tr><td class="dec">111</td><td class="bin">1101111</td><td class="hex">6F</td><td class="ascii">o</td></tr>
    <tr><td class="dec">112</td><td class="bin">1110000</td><td class="hex">70</td><td class="ascii">p</td></tr>
    <tr><td class="dec">113</td><td class="bin">1110001</td><td class="hex">71</td><td class="ascii">q</td></tr>
    <tr><td class="dec">114</td><td class="bin">1110010</td><td class="hex">72</td><td class="ascii">r</td></tr>
    <tr><td class="dec">115</td><td class="bin">1110011</td><td class="hex">73</td><td class="ascii">s</td></tr>
    <tr><td class="dec">116</td><td class="bin">1110100</td><td class="hex">74</td><td class="ascii">t</td></tr>
    <tr><td class="dec">117</td><td class="bin">1110101</td><td class="hex">75</td><td class="ascii">u</td></tr>
    <tr><td class="dec">118</td><td class="bin">1110110</td><td class="hex">76</td><td class="ascii">v</td></tr>
    <tr><td class="dec">119</td><td class="bin">1110111</td><td class="hex">77</td><td class="ascii">w</td></tr>
    <tr><td class="dec">120</td><td class="bin">1111000</td><td class="hex">78</td><td class="ascii">x</td></tr>
    <tr><td class="dec">121</td><td class="bin">1111001</td><td class="hex">79</td><td class="ascii">y</td></tr>
    <tr><td class="dec">122</td><td class="bin">1111010</td><td class="hex">7A</td><td class="ascii">z</td></tr>
    <tr><td class="dec">123</td><td class="bin">1111011</td><td class="hex">7B</td><td class="ascii">{</td></tr>
    <tr><td class="dec">124</td><td class="bin">1111100</td><td class="hex">7C</td><td class="ascii">|</td></tr>
    <tr><td class="dec">125</td><td class="bin">1111101</td><td class="hex">7D</td><td class="ascii">}</td></tr>
    <tr><td class="dec">126</td><td class="bin">1111110</td><td class="hex">7E</td><td class="ascii">~</td></tr>
    <tr><td class="dec">127</td><td class="bin">1111111</td><td class="hex">7F</td><td class="ascii control">DEL</td></tr>        
</table>
<ul>
    <li><span class="control">橙</span>は制御文字（印字されない）</li>
    <li>SP(0x20)は半角ブランク</li>
    <li>'￥'(0x5C)は機種によって'＼'バックスラッシュで印字される</li>
</ul>

<p>参考</p>
<ul>
    <li><a href="https://www.k-cube.co.jp/wakaba/server/ascii_code.html" target="_blank">ASCIIコード表</a>, 参照<time datetime="2024-05-01">2024-05-01</time></li>
</ul>
