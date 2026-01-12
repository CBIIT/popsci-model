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
<svg width="3316pt" height="688pt"
 viewBox="0.00 0.00 3315.50 688.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 684)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-684 3311.5,-684 3311.5,4 -4,4"/>
<!-- program -->
<g id="node1" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M1553,-.5C1553,-.5 1819,-.5 1819,-.5 1825,-.5 1831,-6.5 1831,-12.5 1831,-12.5 1831,-34.5 1831,-34.5 1831,-40.5 1825,-46.5 1819,-46.5 1819,-46.5 1553,-46.5 1553,-46.5 1547,-46.5 1541,-40.5 1541,-34.5 1541,-34.5 1541,-12.5 1541,-12.5 1541,-6.5 1547,-.5 1553,-.5"/>
<text text-anchor="middle" x="1580" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1619,-.5 1619,-46.5 "/>
<text text-anchor="middle" x="1629.5" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1640,-.5 1640,-46.5 "/>
<text text-anchor="middle" x="1725" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="1640,-23.5 1810,-23.5 "/>
<text text-anchor="middle" x="1725" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="1810,-.5 1810,-46.5 "/>
<text text-anchor="middle" x="1820.5" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel -->
<g id="node2" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M12,-484C12,-484 374,-484 374,-484 380,-484 386,-490 386,-496 386,-496 386,-610 386,-610 386,-616 380,-622 374,-622 374,-622 12,-622 12,-622 6,-622 0,-616 0,-610 0,-610 0,-496 0,-496 0,-490 6,-484 12,-484"/>
<text text-anchor="middle" x="67" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="134,-484 134,-622 "/>
<text text-anchor="middle" x="144.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="155,-484 155,-622 "/>
<text text-anchor="middle" x="260" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">person_first_name</text>
<polyline fill="none" stroke="#000000" points="155,-599 365,-599 "/>
<text text-anchor="middle" x="260" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">person_institution</text>
<polyline fill="none" stroke="#000000" points="155,-576 365,-576 "/>
<text text-anchor="middle" x="260" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">person_last_name</text>
<polyline fill="none" stroke="#000000" points="155,-553 365,-553 "/>
<text text-anchor="middle" x="260" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">person_middle_name</text>
<polyline fill="none" stroke="#000000" points="155,-530 365,-530 "/>
<text text-anchor="middle" x="260" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">person_role</text>
<polyline fill="none" stroke="#000000" points="155,-507 365,-507 "/>
<text text-anchor="middle" x="260" y="-491.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_record_id</text>
<polyline fill="none" stroke="#000000" points="365,-484 365,-622 "/>
<text text-anchor="middle" x="375.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1543,-98.5C1543,-98.5 1829,-98.5 1829,-98.5 1835,-98.5 1841,-104.5 1841,-110.5 1841,-110.5 1841,-362.5 1841,-362.5 1841,-368.5 1835,-374.5 1829,-374.5 1829,-374.5 1543,-374.5 1543,-374.5 1537,-374.5 1531,-368.5 1531,-362.5 1531,-362.5 1531,-110.5 1531,-110.5 1531,-104.5 1537,-98.5 1543,-98.5"/>
<text text-anchor="middle" x="1559" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1587,-98.5 1587,-374.5 "/>
<text text-anchor="middle" x="1597.5" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1608,-98.5 1608,-374.5 "/>
<text text-anchor="middle" x="1714" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_collection</text>
<polyline fill="none" stroke="#000000" points="1608,-351.5 1820,-351.5 "/>
<text text-anchor="middle" x="1714" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession_id</text>
<polyline fill="none" stroke="#000000" points="1608,-328.5 1820,-328.5 "/>
<text text-anchor="middle" x="1714" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrollment_beginning_year</text>
<polyline fill="none" stroke="#000000" points="1608,-305.5 1820,-305.5 "/>
<text text-anchor="middle" x="1714" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrollment_ending_year</text>
<polyline fill="none" stroke="#000000" points="1608,-282.5 1820,-282.5 "/>
<text text-anchor="middle" x="1714" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_beginning_year</text>
<polyline fill="none" stroke="#000000" points="1608,-259.5 1820,-259.5 "/>
<text text-anchor="middle" x="1714" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1608,-236.5 1820,-236.5 "/>
<text text-anchor="middle" x="1714" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_design</text>
<polyline fill="none" stroke="#000000" points="1608,-213.5 1820,-213.5 "/>
<text text-anchor="middle" x="1714" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_ending_year</text>
<polyline fill="none" stroke="#000000" points="1608,-190.5 1820,-190.5 "/>
<text text-anchor="middle" x="1714" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1608,-167.5 1820,-167.5 "/>
<text text-anchor="middle" x="1714" y="-152.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1608,-144.5 1820,-144.5 "/>
<text text-anchor="middle" x="1714" y="-129.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_name</text>
<polyline fill="none" stroke="#000000" points="1608,-121.5 1820,-121.5 "/>
<text text-anchor="middle" x="1714" y="-106.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="1820,-98.5 1820,-374.5 "/>
<text text-anchor="middle" x="1830.5" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M284.829,-483.9767C317.9923,-462.1828 356.7197,-440.1256 395,-426 598.638,-350.8565 1220.8341,-282.0246 1520.8295,-252.163"/>
<polygon fill="#000000" stroke="#000000" points="1521.3205,-255.6315 1530.9257,-251.1606 1520.6288,-248.6658 1521.3205,-255.6315"/>
<text text-anchor="middle" x="555.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- study_country -->
<g id="node3" class="node">
<title>study_country</title>
<path fill="none" stroke="#000000" d="M416,-530C416,-530 748,-530 748,-530 754,-530 760,-536 760,-542 760,-542 760,-564 760,-564 760,-570 754,-576 748,-576 748,-576 416,-576 416,-576 410,-576 404,-570 404,-564 404,-564 404,-542 404,-542 404,-536 410,-530 416,-530"/>
<text text-anchor="middle" x="463.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_country</text>
<polyline fill="none" stroke="#000000" points="523,-530 523,-576 "/>
<text text-anchor="middle" x="533.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="544,-530 544,-576 "/>
<text text-anchor="middle" x="641.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_country</text>
<polyline fill="none" stroke="#000000" points="544,-553 739,-553 "/>
<text text-anchor="middle" x="641.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_country_record_id</text>
<polyline fill="none" stroke="#000000" points="739,-530 739,-576 "/>
<text text-anchor="middle" x="749.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_country&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_country&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M608.5061,-529.948C643.0548,-501.1499 706.4713,-452.4505 769,-426 1018.8671,-320.3027 1332.6651,-271.8807 1520.8495,-250.9772"/>
<polygon fill="#000000" stroke="#000000" points="1521.2709,-254.4521 1530.8292,-249.8814 1520.5068,-247.4939 1521.2709,-254.4521"/>
<text text-anchor="middle" x="897.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge9" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1686,-98.2963C1686,-83.0376 1686,-68.7343 1686,-56.8045"/>
<polygon fill="#000000" stroke="#000000" points="1689.5001,-56.5565 1686,-46.5565 1682.5001,-56.5566 1689.5001,-56.5565"/>
<text text-anchor="middle" x="1725" y="-68.8" font-family="Times,serif" font-size="14.00" fill="#000000">belongs_to</text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M790.5,-438C790.5,-438 1197.5,-438 1197.5,-438 1203.5,-438 1209.5,-444 1209.5,-450 1209.5,-450 1209.5,-656 1209.5,-656 1209.5,-662 1203.5,-668 1197.5,-668 1197.5,-668 790.5,-668 790.5,-668 784.5,-668 778.5,-662 778.5,-656 778.5,-656 778.5,-450 778.5,-450 778.5,-444 784.5,-438 790.5,-438"/>
<text text-anchor="middle" x="826.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="874.5,-438 874.5,-668 "/>
<text text-anchor="middle" x="885" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="895.5,-438 895.5,-668 "/>
<text text-anchor="middle" x="1042" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="895.5,-645 1188.5,-645 "/>
<text text-anchor="middle" x="1042" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_first_cancer_diagnosis</text>
<polyline fill="none" stroke="#000000" points="895.5,-622 1188.5,-622 "/>
<text text-anchor="middle" x="1042" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">cancer_diagnosis_disease_morphology</text>
<polyline fill="none" stroke="#000000" points="895.5,-599 1188.5,-599 "/>
<text text-anchor="middle" x="1042" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">cancer_diagnosis_primary_site</text>
<polyline fill="none" stroke="#000000" points="895.5,-576 1188.5,-576 "/>
<text text-anchor="middle" x="1042" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="895.5,-553 1188.5,-553 "/>
<text text-anchor="middle" x="1042" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">ncbi_taxonomy_id</text>
<polyline fill="none" stroke="#000000" points="895.5,-530 1188.5,-530 "/>
<text text-anchor="middle" x="1042" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_case_indicator</text>
<polyline fill="none" stroke="#000000" points="895.5,-507 1188.5,-507 "/>
<text text-anchor="middle" x="1042" y="-491.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="895.5,-484 1188.5,-484 "/>
<text text-anchor="middle" x="1042" y="-468.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="895.5,-461 1188.5,-461 "/>
<text text-anchor="middle" x="1042" y="-445.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="1188.5,-438 1188.5,-668 "/>
<text text-anchor="middle" x="1199" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1193.8962,-437.9682C1201.9949,-433.8478 1210.0508,-429.8424 1218,-426 1316.7103,-378.2864 1430.6785,-331.962 1521.4334,-297.0585"/>
<polygon fill="#000000" stroke="#000000" points="1522.8969,-300.2459 1530.9797,-293.3963 1520.3896,-293.7103 1522.8969,-300.2459"/>
<text text-anchor="middle" x="1338.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- data_collection -->
<g id="node6" class="node">
<title>data_collection</title>
<path fill="none" stroke="#000000" d="M1239.5,-518.5C1239.5,-518.5 1710.5,-518.5 1710.5,-518.5 1716.5,-518.5 1722.5,-524.5 1722.5,-530.5 1722.5,-530.5 1722.5,-575.5 1722.5,-575.5 1722.5,-581.5 1716.5,-587.5 1710.5,-587.5 1710.5,-587.5 1239.5,-587.5 1239.5,-587.5 1233.5,-587.5 1227.5,-581.5 1227.5,-575.5 1227.5,-575.5 1227.5,-530.5 1227.5,-530.5 1227.5,-524.5 1233.5,-518.5 1239.5,-518.5"/>
<text text-anchor="middle" x="1290" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_collection</text>
<polyline fill="none" stroke="#000000" points="1352.5,-518.5 1352.5,-587.5 "/>
<text text-anchor="middle" x="1363" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1373.5,-518.5 1373.5,-587.5 "/>
<text text-anchor="middle" x="1537.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_collection_category</text>
<polyline fill="none" stroke="#000000" points="1373.5,-564.5 1701.5,-564.5 "/>
<text text-anchor="middle" x="1537.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_collection_category_annotation_count</text>
<polyline fill="none" stroke="#000000" points="1373.5,-541.5 1701.5,-541.5 "/>
<text text-anchor="middle" x="1537.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_collection_record_id</text>
<polyline fill="none" stroke="#000000" points="1701.5,-518.5 1701.5,-587.5 "/>
<text text-anchor="middle" x="1712" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- data_collection&#45;&gt;study -->
<g id="edge5" class="edge">
<title>data_collection&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1498.1843,-518.2236C1520.1901,-485.2149 1554.7992,-433.3012 1588.3447,-382.983"/>
<polygon fill="#000000" stroke="#000000" points="1591.3,-384.8596 1593.9349,-374.5977 1585.4757,-380.9767 1591.3,-384.8596"/>
<text text-anchor="middle" x="1638.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1753,-472.5C1753,-472.5 2041,-472.5 2041,-472.5 2047,-472.5 2053,-478.5 2053,-484.5 2053,-484.5 2053,-621.5 2053,-621.5 2053,-627.5 2047,-633.5 2041,-633.5 2041,-633.5 1753,-633.5 1753,-633.5 1747,-633.5 1741,-627.5 1741,-621.5 1741,-621.5 1741,-484.5 1741,-484.5 1741,-478.5 1747,-472.5 1753,-472.5"/>
<text text-anchor="middle" x="1789.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1838,-472.5 1838,-633.5 "/>
<text text-anchor="middle" x="1848.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1859,-472.5 1859,-633.5 "/>
<text text-anchor="middle" x="1945.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">authorship</text>
<polyline fill="none" stroke="#000000" points="1859,-610.5 2032,-610.5 "/>
<text text-anchor="middle" x="1945.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">digital_object_id</text>
<polyline fill="none" stroke="#000000" points="1859,-587.5 2032,-587.5 "/>
<text text-anchor="middle" x="1945.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">journal_citation</text>
<polyline fill="none" stroke="#000000" points="1859,-564.5 2032,-564.5 "/>
<text text-anchor="middle" x="1945.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication_record_id</text>
<polyline fill="none" stroke="#000000" points="1859,-541.5 2032,-541.5 "/>
<text text-anchor="middle" x="1945.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication_title</text>
<polyline fill="none" stroke="#000000" points="1859,-518.5 2032,-518.5 "/>
<text text-anchor="middle" x="1945.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1859,-495.5 2032,-495.5 "/>
<text text-anchor="middle" x="1945.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_publication</text>
<polyline fill="none" stroke="#000000" points="2032,-472.5 2032,-633.5 "/>
<text text-anchor="middle" x="2042.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1843.2098,-472.3148C1825.074,-445.1111 1804.2297,-413.8446 1783.7748,-383.1622"/>
<polygon fill="#000000" stroke="#000000" points="1786.4776,-380.9066 1778.0184,-374.5275 1780.6532,-384.7895 1786.4776,-380.9066"/>
<text text-anchor="middle" x="1855.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- study_state_province_territory -->
<g id="node8" class="node">
<title>study_state_province_territory</title>
<path fill="none" stroke="#000000" d="M2083,-530C2083,-530 2579,-530 2579,-530 2585,-530 2591,-536 2591,-542 2591,-542 2591,-564 2591,-564 2591,-570 2585,-576 2579,-576 2579,-576 2083,-576 2083,-576 2077,-576 2071,-570 2071,-564 2071,-564 2071,-542 2071,-542 2071,-536 2077,-530 2083,-530"/>
<text text-anchor="middle" x="2190.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_state_province_territory</text>
<polyline fill="none" stroke="#000000" points="2310,-530 2310,-576 "/>
<text text-anchor="middle" x="2320.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2331,-530 2331,-576 "/>
<text text-anchor="middle" x="2450.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_state_province_territory</text>
<polyline fill="none" stroke="#000000" points="2331,-553 2570,-553 "/>
<text text-anchor="middle" x="2450.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_state_record_id</text>
<polyline fill="none" stroke="#000000" points="2570,-530 2570,-576 "/>
<text text-anchor="middle" x="2580.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_state_province_territory&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_state_province_territory&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2284.0936,-529.9832C2194.3844,-485.963 1994.6295,-387.9438 1850.6247,-317.281"/>
<polygon fill="#000000" stroke="#000000" points="1851.741,-313.9301 1841.2217,-312.6669 1848.6573,-320.2143 1851.741,-313.9301"/>
<text text-anchor="middle" x="2085.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- associated_link -->
<g id="node9" class="node">
<title>associated_link</title>
<path fill="none" stroke="#000000" d="M2621,-518.5C2621,-518.5 2969,-518.5 2969,-518.5 2975,-518.5 2981,-524.5 2981,-530.5 2981,-530.5 2981,-575.5 2981,-575.5 2981,-581.5 2975,-587.5 2969,-587.5 2969,-587.5 2621,-587.5 2621,-587.5 2615,-587.5 2609,-581.5 2609,-575.5 2609,-575.5 2609,-530.5 2609,-530.5 2609,-524.5 2615,-518.5 2621,-518.5"/>
<text text-anchor="middle" x="2672.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_link</text>
<polyline fill="none" stroke="#000000" points="2736,-518.5 2736,-587.5 "/>
<text text-anchor="middle" x="2746.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2757,-518.5 2757,-587.5 "/>
<text text-anchor="middle" x="2858.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_link_name</text>
<polyline fill="none" stroke="#000000" points="2757,-564.5 2960,-564.5 "/>
<text text-anchor="middle" x="2858.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_link_record_id</text>
<polyline fill="none" stroke="#000000" points="2757,-541.5 2960,-541.5 "/>
<text text-anchor="middle" x="2858.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_link_url</text>
<polyline fill="none" stroke="#000000" points="2960,-518.5 2960,-587.5 "/>
<text text-anchor="middle" x="2970.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- associated_link&#45;&gt;study -->
<g id="edge3" class="edge">
<title>associated_link&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2752.3384,-518.4477C2714.4953,-489.516 2656.5916,-449.3188 2600,-426 2350.3124,-323.115 2038.3981,-273.878 1851.0719,-252.0408"/>
<polygon fill="#000000" stroke="#000000" points="1851.4726,-248.5639 1841.1374,-250.8948 1850.6704,-255.5178 1851.4726,-248.5639"/>
<text text-anchor="middle" x="2610.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- file -->
<g id="node10" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M3010.5,-426.5C3010.5,-426.5 3295.5,-426.5 3295.5,-426.5 3301.5,-426.5 3307.5,-432.5 3307.5,-438.5 3307.5,-438.5 3307.5,-667.5 3307.5,-667.5 3307.5,-673.5 3301.5,-679.5 3295.5,-679.5 3295.5,-679.5 3010.5,-679.5 3010.5,-679.5 3004.5,-679.5 2998.5,-673.5 2998.5,-667.5 2998.5,-667.5 2998.5,-438.5 2998.5,-438.5 2998.5,-432.5 3004.5,-426.5 3010.5,-426.5"/>
<text text-anchor="middle" x="3018" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="3037.5,-426.5 3037.5,-679.5 "/>
<text text-anchor="middle" x="3048" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3058.5,-426.5 3058.5,-679.5 "/>
<text text-anchor="middle" x="3172.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_access_control</text>
<polyline fill="none" stroke="#000000" points="3058.5,-656.5 3286.5,-656.5 "/>
<text text-anchor="middle" x="3172.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_checksum_type</text>
<polyline fill="none" stroke="#000000" points="3058.5,-633.5 3286.5,-633.5 "/>
<text text-anchor="middle" x="3172.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_checksum_value</text>
<polyline fill="none" stroke="#000000" points="3058.5,-610.5 3286.5,-610.5 "/>
<text text-anchor="middle" x="3172.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_compression_status</text>
<polyline fill="none" stroke="#000000" points="3058.5,-587.5 3286.5,-587.5 "/>
<text text-anchor="middle" x="3172.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_description</text>
<polyline fill="none" stroke="#000000" points="3058.5,-564.5 3286.5,-564.5 "/>
<text text-anchor="middle" x="3172.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_format</text>
<polyline fill="none" stroke="#000000" points="3058.5,-541.5 3286.5,-541.5 "/>
<text text-anchor="middle" x="3172.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_location</text>
<polyline fill="none" stroke="#000000" points="3058.5,-518.5 3286.5,-518.5 "/>
<text text-anchor="middle" x="3172.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_name</text>
<polyline fill="none" stroke="#000000" points="3058.5,-495.5 3286.5,-495.5 "/>
<text text-anchor="middle" x="3172.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_size</text>
<polyline fill="none" stroke="#000000" points="3058.5,-472.5 3286.5,-472.5 "/>
<text text-anchor="middle" x="3172.5" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_type</text>
<polyline fill="none" stroke="#000000" points="3058.5,-449.5 3286.5,-449.5 "/>
<text text-anchor="middle" x="3172.5" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_file_uuid</text>
<polyline fill="none" stroke="#000000" points="3286.5,-426.5 3286.5,-679.5 "/>
<text text-anchor="middle" x="3297" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2998.3923,-429.7649C2995.6032,-428.4529 2992.8049,-427.1962 2990,-426 2787.8493,-339.7919 2154.6346,-276.2452 1851.2548,-249.9027"/>
<polygon fill="#000000" stroke="#000000" points="1851.3107,-246.3945 1841.0462,-249.0195 1850.7073,-253.3685 1851.3107,-246.3945"/>
<text text-anchor="middle" x="2990.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
</g>
</svg>
</div>
