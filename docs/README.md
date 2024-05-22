<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

# Population Sciences Data Commons Model
[View model on GitHub Pages](https://cbiit.github.io/popsci-model)



Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/popsci-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="4052pt" height="786pt"
 viewBox="0.00 0.00 4051.50 786.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 782)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-782 4047.5,-782 4047.5,4 -4,4"/>
<!-- study_demographic -->
<g id="node1" class="node">
<title>study_demographic</title>
<path fill="none" stroke="#000000" d="M12,-559C12,-559 442,-559 442,-559 448,-559 454,-565 454,-571 454,-571 454,-754 454,-754 454,-760 448,-766 442,-766 442,-766 12,-766 12,-766 6,-766 0,-760 0,-754 0,-754 0,-571 0,-571 0,-565 6,-559 12,-559"/>
<text text-anchor="middle" x="79" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_demographic</text>
<polyline fill="none" stroke="#000000" points="158,-559 158,-766 "/>
<text text-anchor="middle" x="168.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="179,-559 179,-766 "/>
<text text-anchor="middle" x="306" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="179,-743 433,-743 "/>
<text text-anchor="middle" x="306" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="179,-720 433,-720 "/>
<text text-anchor="middle" x="306" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">ncbi_taxonomy_id</text>
<polyline fill="none" stroke="#000000" points="179,-697 433,-697 "/>
<text text-anchor="middle" x="306" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">ncbi_taxonomy_name</text>
<polyline fill="none" stroke="#000000" points="179,-674 433,-674 "/>
<text text-anchor="middle" x="306" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="179,-651 433,-651 "/>
<text text-anchor="middle" x="306" y="-635.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="179,-628 433,-628 "/>
<text text-anchor="middle" x="306" y="-612.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_maximum_age</text>
<polyline fill="none" stroke="#000000" points="179,-605 433,-605 "/>
<text text-anchor="middle" x="306" y="-589.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_median_age</text>
<polyline fill="none" stroke="#000000" points="179,-582 433,-582 "/>
<text text-anchor="middle" x="306" y="-566.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_minimum_age</text>
<polyline fill="none" stroke="#000000" points="433,-559 433,-766 "/>
<text text-anchor="middle" x="443.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1927,-196.5C1927,-196.5 2189,-196.5 2189,-196.5 2195,-196.5 2201,-202.5 2201,-208.5 2201,-208.5 2201,-483.5 2201,-483.5 2201,-489.5 2195,-495.5 2189,-495.5 2189,-495.5 1927,-495.5 1927,-495.5 1921,-495.5 1915,-489.5 1915,-483.5 1915,-483.5 1915,-208.5 1915,-208.5 1915,-202.5 1921,-196.5 1927,-196.5"/>
<text text-anchor="middle" x="1943" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1971,-196.5 1971,-495.5 "/>
<text text-anchor="middle" x="1981.5" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1992,-196.5 1992,-495.5 "/>
<text text-anchor="middle" x="2086" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_collection</text>
<polyline fill="none" stroke="#000000" points="1992,-472.5 2180,-472.5 "/>
<text text-anchor="middle" x="2086" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession_id</text>
<polyline fill="none" stroke="#000000" points="1992,-449.5 2180,-449.5 "/>
<text text-anchor="middle" x="2086" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1992,-426.5 2180,-426.5 "/>
<text text-anchor="middle" x="2086" y="-411.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_beginning_year</text>
<polyline fill="none" stroke="#000000" points="1992,-403.5 2180,-403.5 "/>
<text text-anchor="middle" x="2086" y="-388.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1992,-380.5 2180,-380.5 "/>
<text text-anchor="middle" x="2086" y="-365.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_design</text>
<polyline fill="none" stroke="#000000" points="1992,-357.5 2180,-357.5 "/>
<text text-anchor="middle" x="2086" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_ending_year</text>
<polyline fill="none" stroke="#000000" points="1992,-334.5 2180,-334.5 "/>
<text text-anchor="middle" x="2086" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1992,-311.5 2180,-311.5 "/>
<text text-anchor="middle" x="2086" y="-296.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1992,-288.5 2180,-288.5 "/>
<text text-anchor="middle" x="2086" y="-273.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_phs_id</text>
<polyline fill="none" stroke="#000000" points="1992,-265.5 2180,-265.5 "/>
<text text-anchor="middle" x="2086" y="-250.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_name</text>
<polyline fill="none" stroke="#000000" points="1992,-242.5 2180,-242.5 "/>
<text text-anchor="middle" x="2086" y="-227.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="1992,-219.5 2180,-219.5 "/>
<text text-anchor="middle" x="2086" y="-204.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="2180,-196.5 2180,-495.5 "/>
<text text-anchor="middle" x="2190.5" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_demographic&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_demographic&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M428.068,-558.9871C439.7465,-554.5812 451.4411,-550.538 463,-547 564.2715,-516.0019 593.9976,-527.8306 699,-514 1135.979,-456.4425 1652.799,-394.1396 1904.6287,-364.1525"/>
<polygon fill="#000000" stroke="#000000" points="1905.0629,-367.6256 1914.5791,-362.968 1904.2355,-360.6747 1905.0629,-367.6256"/>
<text text-anchor="middle" x="756.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- study_country -->
<g id="node2" class="node">
<title>study_country</title>
<path fill="none" stroke="#000000" d="M484,-644.5C484,-644.5 740,-644.5 740,-644.5 746,-644.5 752,-650.5 752,-656.5 752,-656.5 752,-668.5 752,-668.5 752,-674.5 746,-680.5 740,-680.5 740,-680.5 484,-680.5 484,-680.5 478,-680.5 472,-674.5 472,-668.5 472,-668.5 472,-656.5 472,-656.5 472,-650.5 478,-644.5 484,-644.5"/>
<text text-anchor="middle" x="531.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_country</text>
<polyline fill="none" stroke="#000000" points="591,-644.5 591,-680.5 "/>
<text text-anchor="middle" x="601.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="612,-644.5 612,-680.5 "/>
<text text-anchor="middle" x="671.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_country</text>
<polyline fill="none" stroke="#000000" points="731,-644.5 731,-680.5 "/>
<text text-anchor="middle" x="741.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_country&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_country&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M629.2919,-644.1657C655.2083,-617.9351 706.8891,-570.2988 761,-547 964.5727,-459.3469 1607.7424,-388.8389 1904.829,-360.0363"/>
<polygon fill="#000000" stroke="#000000" points="1905.1999,-363.5168 1914.8169,-359.071 1904.5265,-356.5493 1905.1999,-363.5168"/>
<text text-anchor="middle" x="896.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- study_state_province_territory -->
<g id="node3" class="node">
<title>study_state_province_territory</title>
<path fill="none" stroke="#000000" d="M782,-644.5C782,-644.5 1278,-644.5 1278,-644.5 1284,-644.5 1290,-650.5 1290,-656.5 1290,-656.5 1290,-668.5 1290,-668.5 1290,-674.5 1284,-680.5 1278,-680.5 1278,-680.5 782,-680.5 782,-680.5 776,-680.5 770,-674.5 770,-668.5 770,-668.5 770,-656.5 770,-656.5 770,-650.5 776,-644.5 782,-644.5"/>
<text text-anchor="middle" x="889.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_state_province_territory</text>
<polyline fill="none" stroke="#000000" points="1009,-644.5 1009,-680.5 "/>
<text text-anchor="middle" x="1019.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1030,-644.5 1030,-680.5 "/>
<text text-anchor="middle" x="1149.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_state_province_territory</text>
<polyline fill="none" stroke="#000000" points="1269,-644.5 1269,-680.5 "/>
<text text-anchor="middle" x="1279.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_state_province_territory&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_state_province_territory&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1067.1799,-644.4665C1118.4634,-620.0736 1214.2002,-576.2567 1299,-547 1505.1589,-475.8732 1750.0769,-415.1447 1904.791,-379.5971"/>
<polygon fill="#000000" stroke="#000000" points="1905.8843,-382.9374 1914.8499,-377.2922 1904.3208,-376.1142 1905.8843,-382.9374"/>
<text text-anchor="middle" x="1437.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- comorbidity -->
<g id="node4" class="node">
<title>comorbidity</title>
<path fill="none" stroke="#000000" d="M1320.5,-644.5C1320.5,-644.5 1647.5,-644.5 1647.5,-644.5 1653.5,-644.5 1659.5,-650.5 1659.5,-656.5 1659.5,-656.5 1659.5,-668.5 1659.5,-668.5 1659.5,-674.5 1653.5,-680.5 1647.5,-680.5 1647.5,-680.5 1320.5,-680.5 1320.5,-680.5 1314.5,-680.5 1308.5,-674.5 1308.5,-668.5 1308.5,-668.5 1308.5,-656.5 1308.5,-656.5 1308.5,-650.5 1314.5,-644.5 1320.5,-644.5"/>
<text text-anchor="middle" x="1360" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="1411.5,-644.5 1411.5,-680.5 "/>
<text text-anchor="middle" x="1422" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1432.5,-644.5 1432.5,-680.5 "/>
<text text-anchor="middle" x="1535.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_disease_term</text>
<polyline fill="none" stroke="#000000" points="1638.5,-644.5 1638.5,-680.5 "/>
<text text-anchor="middle" x="1649" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- comorbidity&#45;&gt;study -->
<g id="edge8" class="edge">
<title>comorbidity&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1511.4686,-644.3715C1547.2283,-620.9993 1611.9092,-579.5002 1669,-547 1745.8159,-503.2708 1833.1033,-457.7988 1905.5024,-421.1886"/>
<polygon fill="#000000" stroke="#000000" points="1907.3589,-424.1721 1914.7082,-416.5406 1904.204,-417.9234 1907.3589,-424.1721"/>
<text text-anchor="middle" x="1778.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- project -->
<g id="node9" class="node">
<title>project</title>
<path fill="none" stroke="#000000" d="M1850.5,-98.5C1850.5,-98.5 2095.5,-98.5 2095.5,-98.5 2101.5,-98.5 2107.5,-104.5 2107.5,-110.5 2107.5,-110.5 2107.5,-132.5 2107.5,-132.5 2107.5,-138.5 2101.5,-144.5 2095.5,-144.5 2095.5,-144.5 1850.5,-144.5 1850.5,-144.5 1844.5,-144.5 1838.5,-138.5 1838.5,-132.5 1838.5,-132.5 1838.5,-110.5 1838.5,-110.5 1838.5,-104.5 1844.5,-98.5 1850.5,-98.5"/>
<text text-anchor="middle" x="1872.5" y="-117.8" font-family="Times,serif" font-size="14.00" fill="#000000">project</text>
<polyline fill="none" stroke="#000000" points="1906.5,-98.5 1906.5,-144.5 "/>
<text text-anchor="middle" x="1917" y="-117.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1927.5,-98.5 1927.5,-144.5 "/>
<text text-anchor="middle" x="2007" y="-129.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_name</text>
<polyline fill="none" stroke="#000000" points="1927.5,-121.5 2086.5,-121.5 "/>
<text text-anchor="middle" x="2007" y="-106.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_short_name</text>
<polyline fill="none" stroke="#000000" points="2086.5,-98.5 2086.5,-144.5 "/>
<text text-anchor="middle" x="2097" y="-117.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;project -->
<g id="edge2" class="edge">
<title>study&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M2001.3038,-196.2552C1995.4035,-180.6716 1989.9157,-166.1773 1985.373,-154.1794"/>
<polygon fill="#000000" stroke="#000000" points="1988.6054,-152.832 1981.7912,-144.7192 1982.059,-155.3107 1988.6054,-152.832"/>
<text text-anchor="middle" x="2033" y="-166.8" font-family="Times,serif" font-size="14.00" fill="#000000">belongs_to</text>
</g>
<!-- program -->
<g id="node10" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M1925,-.5C1925,-.5 2191,-.5 2191,-.5 2197,-.5 2203,-6.5 2203,-12.5 2203,-12.5 2203,-34.5 2203,-34.5 2203,-40.5 2197,-46.5 2191,-46.5 2191,-46.5 1925,-46.5 1925,-46.5 1919,-46.5 1913,-40.5 1913,-34.5 1913,-34.5 1913,-12.5 1913,-12.5 1913,-6.5 1919,-.5 1925,-.5"/>
<text text-anchor="middle" x="1952" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1991,-.5 1991,-46.5 "/>
<text text-anchor="middle" x="2001.5" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2012,-.5 2012,-46.5 "/>
<text text-anchor="middle" x="2097" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="2012,-23.5 2182,-23.5 "/>
<text text-anchor="middle" x="2097" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="2182,-.5 2182,-46.5 "/>
<text text-anchor="middle" x="2192.5" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge1" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M2113.6452,-196.2711C2119.8626,-163.9673 2122.0624,-129.9293 2116,-98 2113.0595,-82.513 2111.9081,-78.0054 2103,-65 2100.4307,-61.2489 2097.4634,-57.5926 2094.3029,-54.1041"/>
<polygon fill="#000000" stroke="#000000" points="2096.639,-51.4862 2087.1549,-46.7637 2091.6239,-56.3698 2096.639,-51.4862"/>
<text text-anchor="middle" x="2159" y="-117.8" font-family="Times,serif" font-size="14.00" fill="#000000">belongs_to</text>
</g>
<!-- data_file -->
<g id="node6" class="node">
<title>data_file</title>
<path fill="none" stroke="#000000" d="M1690,-547.5C1690,-547.5 2014,-547.5 2014,-547.5 2020,-547.5 2026,-553.5 2026,-559.5 2026,-559.5 2026,-765.5 2026,-765.5 2026,-771.5 2020,-777.5 2014,-777.5 2014,-777.5 1690,-777.5 1690,-777.5 1684,-777.5 1678,-771.5 1678,-765.5 1678,-765.5 1678,-559.5 1678,-559.5 1678,-553.5 1684,-547.5 1690,-547.5"/>
<text text-anchor="middle" x="1717" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_file</text>
<polyline fill="none" stroke="#000000" points="1756,-547.5 1756,-777.5 "/>
<text text-anchor="middle" x="1766.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1777,-547.5 1777,-777.5 "/>
<text text-anchor="middle" x="1891" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_checksum_type</text>
<polyline fill="none" stroke="#000000" points="1777,-754.5 2005,-754.5 "/>
<text text-anchor="middle" x="1891" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_checksum_value</text>
<polyline fill="none" stroke="#000000" points="1777,-731.5 2005,-731.5 "/>
<text text-anchor="middle" x="1891" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_compression_status</text>
<polyline fill="none" stroke="#000000" points="1777,-708.5 2005,-708.5 "/>
<text text-anchor="middle" x="1891" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_description</text>
<polyline fill="none" stroke="#000000" points="1777,-685.5 2005,-685.5 "/>
<text text-anchor="middle" x="1891" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_format</text>
<polyline fill="none" stroke="#000000" points="1777,-662.5 2005,-662.5 "/>
<text text-anchor="middle" x="1891" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_location</text>
<polyline fill="none" stroke="#000000" points="1777,-639.5 2005,-639.5 "/>
<text text-anchor="middle" x="1891" y="-624.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_name</text>
<polyline fill="none" stroke="#000000" points="1777,-616.5 2005,-616.5 "/>
<text text-anchor="middle" x="1891" y="-601.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_size</text>
<polyline fill="none" stroke="#000000" points="1777,-593.5 2005,-593.5 "/>
<text text-anchor="middle" x="1891" y="-578.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_type</text>
<polyline fill="none" stroke="#000000" points="1777,-570.5 2005,-570.5 "/>
<text text-anchor="middle" x="1891" y="-555.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_uuid</text>
<polyline fill="none" stroke="#000000" points="2005,-547.5 2005,-777.5 "/>
<text text-anchor="middle" x="2015.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- data_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>data_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1926.9535,-547.3409C1936.0893,-533.3046 1945.5437,-518.7787 1954.9982,-504.2528"/>
<polygon fill="#000000" stroke="#000000" points="1958.0408,-505.9942 1960.5624,-495.7038 1952.174,-502.1757 1958.0408,-505.9942"/>
<text text-anchor="middle" x="2000.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- primary_diagnosis -->
<g id="node7" class="node">
<title>primary_diagnosis</title>
<path fill="none" stroke="#000000" d="M2056,-644.5C2056,-644.5 2474,-644.5 2474,-644.5 2480,-644.5 2486,-650.5 2486,-656.5 2486,-656.5 2486,-668.5 2486,-668.5 2486,-674.5 2480,-680.5 2474,-680.5 2474,-680.5 2056,-680.5 2056,-680.5 2050,-680.5 2044,-674.5 2044,-668.5 2044,-668.5 2044,-656.5 2044,-656.5 2044,-650.5 2050,-644.5 2056,-644.5"/>
<text text-anchor="middle" x="2118.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2193,-644.5 2193,-680.5 "/>
<text text-anchor="middle" x="2203.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2214,-644.5 2214,-680.5 "/>
<text text-anchor="middle" x="2339.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_disease_term</text>
<polyline fill="none" stroke="#000000" points="2465,-644.5 2465,-680.5 "/>
<text text-anchor="middle" x="2475.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- primary_diagnosis&#45;&gt;study -->
<g id="edge12" class="edge">
<title>primary_diagnosis&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2252.9761,-644.1156C2234.6737,-616.1315 2198.0726,-560.1689 2161.4755,-504.2126"/>
<polygon fill="#000000" stroke="#000000" points="2164.2447,-502.0522 2155.842,-495.5989 2158.3864,-505.8837 2164.2447,-502.0522"/>
<text text-anchor="middle" x="2231.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2516,-593.5C2516,-593.5 2844,-593.5 2844,-593.5 2850,-593.5 2856,-599.5 2856,-605.5 2856,-605.5 2856,-719.5 2856,-719.5 2856,-725.5 2850,-731.5 2844,-731.5 2844,-731.5 2516,-731.5 2516,-731.5 2510,-731.5 2504,-725.5 2504,-719.5 2504,-719.5 2504,-605.5 2504,-605.5 2504,-599.5 2510,-593.5 2516,-593.5"/>
<text text-anchor="middle" x="2571" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2638,-593.5 2638,-731.5 "/>
<text text-anchor="middle" x="2648.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2659,-593.5 2659,-731.5 "/>
<text text-anchor="middle" x="2747" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">person_email_address</text>
<polyline fill="none" stroke="#000000" points="2659,-708.5 2835,-708.5 "/>
<text text-anchor="middle" x="2747" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">person_first_name</text>
<polyline fill="none" stroke="#000000" points="2659,-685.5 2835,-685.5 "/>
<text text-anchor="middle" x="2747" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">person_last_name</text>
<polyline fill="none" stroke="#000000" points="2659,-662.5 2835,-662.5 "/>
<text text-anchor="middle" x="2747" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">person_middle_name</text>
<polyline fill="none" stroke="#000000" points="2659,-639.5 2835,-639.5 "/>
<text text-anchor="middle" x="2747" y="-624.3" font-family="Times,serif" font-size="14.00" fill="#000000">person_orcid_id</text>
<polyline fill="none" stroke="#000000" points="2659,-616.5 2835,-616.5 "/>
<text text-anchor="middle" x="2747" y="-601.3" font-family="Times,serif" font-size="14.00" fill="#000000">person_role</text>
<polyline fill="none" stroke="#000000" points="2835,-593.5 2835,-731.5 "/>
<text text-anchor="middle" x="2845.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2574.2478,-593.2691C2548.673,-577.4256 2521.1608,-561.1091 2495,-547 2402.6313,-497.1836 2295.6402,-447.8392 2210.6425,-410.5084"/>
<polygon fill="#000000" stroke="#000000" points="2212.0046,-407.2841 2201.4406,-406.4761 2209.1951,-413.6955 2212.0046,-407.2841"/>
<text text-anchor="middle" x="2518.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- project&#45;&gt;program -->
<g id="edge3" class="edge">
<title>project&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1993.1438,-98.2754C2004.5764,-85.0943 2019.0261,-68.4346 2031.3834,-54.1874"/>
<polygon fill="#000000" stroke="#000000" points="2034.0925,-56.4056 2038.0008,-46.5579 2028.8045,-51.819 2034.0925,-56.4056"/>
<text text-anchor="middle" x="2060" y="-68.8" font-family="Times,serif" font-size="14.00" fill="#000000">belongs_to</text>
</g>
<!-- associated_link -->
<g id="node11" class="node">
<title>associated_link</title>
<path fill="none" stroke="#000000" d="M2886,-628C2886,-628 3204,-628 3204,-628 3210,-628 3216,-634 3216,-640 3216,-640 3216,-685 3216,-685 3216,-691 3210,-697 3204,-697 3204,-697 2886,-697 2886,-697 2880,-697 2874,-691 2874,-685 2874,-685 2874,-640 2874,-640 2874,-634 2880,-628 2886,-628"/>
<text text-anchor="middle" x="2937.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_link</text>
<polyline fill="none" stroke="#000000" points="3001,-628 3001,-697 "/>
<text text-anchor="middle" x="3011.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3022,-628 3022,-697 "/>
<text text-anchor="middle" x="3108.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_link_id</text>
<polyline fill="none" stroke="#000000" points="3022,-674 3195,-674 "/>
<text text-anchor="middle" x="3108.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_link_name</text>
<polyline fill="none" stroke="#000000" points="3022,-651 3195,-651 "/>
<text text-anchor="middle" x="3108.5" y="-635.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_link_url</text>
<polyline fill="none" stroke="#000000" points="3195,-628 3195,-697 "/>
<text text-anchor="middle" x="3205.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- associated_link&#45;&gt;study -->
<g id="edge7" class="edge">
<title>associated_link&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3000.3422,-627.9502C2965.2628,-602.3131 2914.2639,-568.2536 2865,-547 2647.4941,-453.1628 2377.3226,-397.0463 2211.3251,-368.843"/>
<polygon fill="#000000" stroke="#000000" points="2211.4798,-365.3198 2201.037,-367.1082 2210.3158,-372.2223 2211.4798,-365.3198"/>
<text text-anchor="middle" x="2859.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M3246,-593.5C3246,-593.5 3518,-593.5 3518,-593.5 3524,-593.5 3530,-599.5 3530,-605.5 3530,-605.5 3530,-719.5 3530,-719.5 3530,-725.5 3524,-731.5 3518,-731.5 3518,-731.5 3246,-731.5 3246,-731.5 3240,-731.5 3234,-725.5 3234,-719.5 3234,-719.5 3234,-605.5 3234,-605.5 3234,-599.5 3240,-593.5 3246,-593.5"/>
<text text-anchor="middle" x="3282.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="3331,-593.5 3331,-731.5 "/>
<text text-anchor="middle" x="3341.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3352,-593.5 3352,-731.5 "/>
<text text-anchor="middle" x="3430.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">authorship</text>
<polyline fill="none" stroke="#000000" points="3352,-708.5 3509,-708.5 "/>
<text text-anchor="middle" x="3430.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">digital_object_id</text>
<polyline fill="none" stroke="#000000" points="3352,-685.5 3509,-685.5 "/>
<text text-anchor="middle" x="3430.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">journal_citation</text>
<polyline fill="none" stroke="#000000" points="3352,-662.5 3509,-662.5 "/>
<text text-anchor="middle" x="3430.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication_title</text>
<polyline fill="none" stroke="#000000" points="3352,-639.5 3509,-639.5 "/>
<text text-anchor="middle" x="3430.5" y="-624.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="3352,-616.5 3509,-616.5 "/>
<text text-anchor="middle" x="3430.5" y="-601.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_publication</text>
<polyline fill="none" stroke="#000000" points="3509,-593.5 3509,-731.5 "/>
<text text-anchor="middle" x="3519.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge6" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3302.8944,-593.3271C3279.2048,-575.7582 3252.2433,-558.5959 3225,-547 3044.4509,-470.1507 2484.285,-396.1493 2211.0275,-363.4785"/>
<polygon fill="#000000" stroke="#000000" points="2211.3737,-359.9951 2201.0296,-362.2863 2210.5448,-366.9458 2211.3737,-359.9951"/>
<text text-anchor="middle" x="3231.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- data_collection -->
<g id="node13" class="node">
<title>data_collection</title>
<path fill="none" stroke="#000000" d="M3560.5,-639.5C3560.5,-639.5 4031.5,-639.5 4031.5,-639.5 4037.5,-639.5 4043.5,-645.5 4043.5,-651.5 4043.5,-651.5 4043.5,-673.5 4043.5,-673.5 4043.5,-679.5 4037.5,-685.5 4031.5,-685.5 4031.5,-685.5 3560.5,-685.5 3560.5,-685.5 3554.5,-685.5 3548.5,-679.5 3548.5,-673.5 3548.5,-673.5 3548.5,-651.5 3548.5,-651.5 3548.5,-645.5 3554.5,-639.5 3560.5,-639.5"/>
<text text-anchor="middle" x="3611" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_collection</text>
<polyline fill="none" stroke="#000000" points="3673.5,-639.5 3673.5,-685.5 "/>
<text text-anchor="middle" x="3684" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3694.5,-639.5 3694.5,-685.5 "/>
<text text-anchor="middle" x="3858.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_collection_category</text>
<polyline fill="none" stroke="#000000" points="3694.5,-662.5 4022.5,-662.5 "/>
<text text-anchor="middle" x="3858.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_collection_category_annotation_count</text>
<polyline fill="none" stroke="#000000" points="4022.5,-639.5 4022.5,-685.5 "/>
<text text-anchor="middle" x="4033" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- data_collection&#45;&gt;study -->
<g id="edge5" class="edge">
<title>data_collection&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3754.6674,-639.4262C3705.0245,-612.79 3618.4811,-569.7374 3539,-547 3067.0258,-411.9807 2483.7841,-366.7487 2211.513,-352.3359"/>
<polygon fill="#000000" stroke="#000000" points="2211.3342,-348.8219 2201.1651,-351.7951 2210.9687,-355.8124 2211.3342,-348.8219"/>
<text text-anchor="middle" x="3518.5" y="-517.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
</g>
</svg>
</div>
