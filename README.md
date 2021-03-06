GKC Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/GKC-Project/GKC.svg?branch=master)](https://travis-ci.org/GKC-Project/GKC) [![GitHub version](https://badge.fury.io/gh/GKC-Project%2FGKC.svg)](https://badge.fury.io/gh/GKC-Project%2FGKC)

GKC is a cutting-edge cryptocurrency with many functions that most other cryptocurrencies do not have.

1. The POS function design with entrusted PO is adopted, and the number of DPOS nodes is not limited. Currently, there are more than 110 effective DPOS nodes;
2. Use sigma protocol for anonymous transactions;
3. Fast transactions with guaranteed zero confirmation transactions, which we call SwiftTX;
4. Decentralized blockchain voting provides consensus for the advanced consensus-based Masternode technology, which is used to protect the network and provide the above functions. Each Masternode has a 10K GKC mortgage;
5. Integrated EVM virtual, with Turing complete smart contract.

### Build
See depends/README.md


### Coin Specs
<table>
<tr><td>Algo</td><td>scrypt</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>PoW Coin Supply</td><td>23,509,830 GKC</td></tr>
<tr><td>PoS Coin Supply</td><td>8,999,423 GKC</td></tr>
<tr><td>Season Supply</td><td>3,744,000 GKC</td></tr>
<tr><td>Total Supply</td><td>36,253,253 GKC</td></tr>
</table>


### PoW Rewards Breakdown

<table>
     <th>First Block</th> <th>Last Block</th> <th>Miner            </th> <th>Total            </th>
<tr> <td>          1</td> <td>         1</td> <td>23000000.00000000</td> <td>23000000.00000000</td> </tr>
<tr> <td>          2</td> <td>      3000</td> <td>     170.00000000</td> <td>  509830.00000000</td> </tr>
<tr> <td>      Total</td> <td>          </td> <td>                 </td> <td>23509830.00000000</td> </tr>
</table>


### PoS Rewards Breakdown

<table>
<th>First Block</th>	<th>Last Block</th>	<th>Miner</th>	   <th>Masternodes</th>	    <th>Entrust</th>	    <th>Total</th>	            <th>Acc</th>
<tr><td>    3001</td>	<td>538680	</td>   <td>1.20000000</td> <td>0.60000000</td> 	<td>6.60000000</td> 	<td>4499712.00000000</td> 	<td>4499712.00000000</td></tr> 
<tr><td>  538681</td>	<td>1074360	</td>   <td>0.60000000</td> <td>0.30000000</td> 	<td>3.30000000</td> 	<td>2249856.00000000</td> 	<td>6749568.00000000</td></tr> 
<tr><td> 1074361</td>	<td>1610040	</td>   <td>0.30000000</td> <td>0.15000000</td> 	<td>1.65000000</td> 	<td>1124928.00000000</td> 	<td>7874496.00000000</td></tr> 
<tr><td> 1610041</td>	<td>2145720	</td>   <td>0.15000000</td> <td>0.07500000</td> 	<td>0.82500000</td> 	<td> 562464.00000000</td> 	<td>8436960.00000000</td></tr> 
<tr><td> 2145721</td>	<td>2681400	</td>   <td>0.07500000</td> <td>0.03750000</td> 	<td>0.41250000</td> 	<td> 281232.00000000</td> 	<td>8718192.00000000</td></tr> 
<tr><td> 2681401</td>	<td>3217080	</td>   <td>0.03750000</td> <td>0.01875000</td> 	<td>0.20625000</td> 	<td> 140616.00000000</td> 	<td>8858808.00000000</td></tr> 
<tr><td> 3217081</td>	<td>3752760	</td>   <td>0.01875000</td> <td>0.00937500</td> 	<td>0.10312500</td> 	<td>  70308.00000000</td> 	<td>8929116.00000000</td></tr> 
<tr><td> 3752761</td>	<td>4288440	</td>   <td>0.00937500</td> <td>0.00468750</td> 	<td>0.05156250</td> 	<td>  35154.00000000</td> 	<td>8964270.00000000</td></tr> 
<tr><td> 4288441</td>	<td>4824120	</td>   <td>0.00468750</td> <td>0.00234375</td> 	<td>0.02578125</td> 	<td>  17577.00000000</td> 	<td>8981847.00000000</td></tr> 
<tr><td> 4824121</td>	<td>5359800	</td>   <td>0.00234375</td> <td>0.00117188</td> 	<td>0.01289063</td> 	<td>   8788.50000000</td> 	<td>8990635.50000000</td></tr> 
<tr><td> 5359801</td>	<td>5895480	</td>   <td>0.00117188</td> <td>0.00058594</td> 	<td>0.00644531</td> 	<td>   4394.25000000</td> 	<td>8995029.75000000</td></tr> 
<tr><td> 5895481</td>	<td>6431160	</td>   <td>0.00058594</td> <td>0.00029297</td> 	<td>0.00322266</td> 	<td>   2197.12500000</td> 	<td>8997226.87500000</td></tr> 
<tr><td> 6431161</td>	<td>6966840	</td>   <td>0.00029297</td> <td>0.00014648</td> 	<td>0.00161133</td> 	<td>   1098.56250000</td> 	<td>8998325.43750000</td></tr> 
<tr><td> 6966841</td>	<td>7502520	</td>   <td>0.00014648</td> <td>0.00007324</td> 	<td>0.00080566</td> 	<td>    549.28125000</td> 	<td>8998874.71875000</td></tr> 
<tr><td> 7502521</td>	<td>8038200	</td>   <td>0.00007324</td> <td>0.00003662</td> 	<td>0.00040283</td> 	<td>    274.64062500</td> 	<td>8999149.35937500</td></tr> 
<tr><td> 8038201</td>	<td>8573880	</td>   <td>0.00003662</td> <td>0.00001831</td> 	<td>0.00020142</td> 	<td>    137.32031250</td> 	<td>8999286.67968750</td></tr> 
<tr><td> 8573881</td>	<td>9109560	</td>   <td>0.00001831</td> <td>0.00000916</td> 	<td>0.00010071</td> 	<td>     68.66015625</td> 	<td>8999355.33984375</td></tr> 
<tr><td> 9109561</td>	<td>9645240	</td>   <td>0.00000916</td> <td>0.00000458</td> 	<td>0.00005035</td> 	<td>     34.33007813</td> 	<td>8999389.66992187</td></tr> 
<tr><td> 9645241</td>	<td>10180920</td>	<td>0.00000458</td>	<td>0.00000229</td> 	<td>0.00002518</td> 	<td>     17.16503906</td> 	<td>8999406.83496094</td></tr> 
<tr><td>10180921</td>	<td>10716600</td>	<td>0.00000229</td>	<td>0.00000114</td> 	<td>0.00001259</td> 	<td>      8.58251953</td> 	<td>8999415.41748047</td></tr> 
<tr><td>10716601</td>	<td>11252280</td>	<td>0.00000114</td>	<td>0.00000057</td> 	<td>0.00000629</td> 	<td>      4.29125977</td> 	<td>8999419.70874023</td></tr> 
<tr><td>11252281</td>	<td>11787960</td>	<td>0.00000057</td>	<td>0.00000029</td> 	<td>0.00000315</td> 	<td>      2.14562988</td> 	<td>8999421.85437012</td></tr> 
<tr><td>11787961</td>	<td>12323640</td>	<td>0.00000029</td>	<td>0.00000014</td> 	<td>0.00000157</td> 	<td>      1.07281494</td> 	<td>8999422.92718506</td></tr> 
<tr><td>12323641</td>	<td>12859320</td>	<td>0.00000014</td>	<td>0.00000007</td> 	<td>0.00000079</td> 	<td>      0.53640747</td> 	<td>8999423.46359253</td></tr> 
<tr><td>12859321</td>	<td>13395000</td>	<td>0.00000007</td>	<td>0.00000004</td> 	<td>0.00000039</td> 	<td>      0.26820374</td> 	<td>8999423.73179626</td></tr> 
<tr><td>13395001</td>	<td>13930680</td>	<td>0.00000004</td>	<td>0.00000002</td> 	<td>0.00000020</td> 	<td>      0.13410187</td> 	<td>8999423.86589813</td></tr> 
<tr><td>13930681</td>	<td>14466360</td>	<td>0.00000002</td>	<td>0.00000001</td> 	<td>0.00000010</td> 	<td>      0.06705093</td> 	<td>8999423.93294906</td></tr> 
<tr><td>14466361</td>	<td>15002040</td>	<td>0.00000001</td>	<td>0.00000000</td> 	<td>0.00000005</td> 	<td>      0.03352547</td> 	<td>8999423.96647453</td></tr> 
<tr><td>15002041</td>	<td>INF	    </td>   <td>0.00000000</td> <td>0.00000000</td> 	<td>0.00000002</td> 	<td>      0.00000000</td> 	<td>8999423.96647453</td></tr> 
<tr><td>Total	</td>	<td>        </td>	<td>          </td>	<td>          </td>     <td>          </td>     <td>8999423.96647453</td>	<td>                </td> 
</table>


### Season Rewards Breakdown

<table>
<th>First Block</th>	<th>Last Block</th>	<th>Season</th>	<th>Reward</th>	    <th>Total</th>	            <th>Acc</th>
<tr><td>    3001</td>	<td>  538680</td>	<td>12</td><td>156000.00000000</td> <td>1872000.00000000</td> 	<td>1872000.00000000</td></tr> 
<tr><td>  538681</td>	<td> 1074360</td>	<td>12</td><td>78000.00000000</td> 	<td> 936000.00000000</td> 	<td>2808000.00000000</td></tr> 
<tr><td> 1074361</td>	<td> 1610040</td>	<td>12</td><td>39000.00000000</td> 	<td> 468000.00000000</td> 	<td>3276000.00000000</td></tr> 
<tr><td> 1610041</td>	<td> 2145720</td>	<td>12</td><td>19500.00000000</td> 	<td> 234000.00000000</td> 	<td>3510000.00000000</td></tr> 
<tr><td> 2145721</td>	<td> 2681400</td>	<td>12</td><td> 9750.00000000</td> 	<td> 117000.00000000</td> 	<td>3627000.00000000</td></tr> 
<tr><td> 2681401</td>	<td> 3217080</td>	<td>12</td><td> 4875.00000000</td> 	<td>  58500.00000000</td> 	<td>3685500.00000000</td></tr> 
<tr><td> 3217081</td>	<td> 3752760</td>	<td>12</td><td> 2437.50000000</td> 	<td>  29250.00000000</td> 	<td>3714750.00000000</td></tr> 
<tr><td> 3752761</td>	<td> 4288440</td>	<td>12</td><td> 1218.75000000</td> 	<td>  14625.00000000</td> 	<td>3729375.00000000</td></tr> 
<tr><td> 4288441</td>	<td> 4824120</td>	<td>12</td><td>  609.37500000</td> 	<td>   7312.50000000</td> 	<td>3736687.50000000</td></tr> 
<tr><td> 4824121</td>	<td> 5359800</td>	<td>12</td><td>  304.68750000</td> 	<td>   3656.25000000</td> 	<td>3740343.75000000</td></tr> 
<tr><td> 5359801</td>	<td> 5895480</td>	<td>12</td><td>  152.34375000</td> 	<td>   1828.12500000</td> 	<td>3742171.87500000</td></tr> 
<tr><td> 5895481</td>	<td> 6431160</td>	<td>12</td><td>   76.17187500</td> 	<td>    914.06250000</td> 	<td>3743085.93750000</td></tr> 
<tr><td> 6431161</td>	<td> 6966840</td>	<td>12</td><td>   38.08593750</td> 	<td>    457.03125000</td> 	<td>3743542.96875000</td></tr> 
<tr><td> 6966841</td>	<td> 7502520</td>	<td>12</td><td>   19.04296875</td> 	<td>    228.51562500</td> 	<td>3743771.48437500</td></tr> 
<tr><td> 7502521</td>	<td> 8038200</td>	<td>12</td><td>    9.52148438</td> 	<td>    114.25781250</td> 	<td>3743885.74218750</td></tr> 
<tr><td> 8038201</td>	<td> 8573880</td>	<td>12</td><td>    4.76074219</td> 	<td>     57.12890625</td> 	<td>3743942.87109375</td></tr> 
<tr><td> 8573881</td>	<td> 9109560</td>	<td>12</td><td>    2.38037109</td> 	<td>     28.56445313</td> 	<td>3743971.43554687</td></tr> 
<tr><td> 9109561</td>	<td> 9645240</td>	<td>12</td><td>    1.19018555</td> 	<td>     14.28222656</td> 	<td>3743985.71777344</td></tr> 
<tr><td> 9645241</td>	<td>10180920</td>	<td>12</td><td>    0.59509277</td> 	<td>      7.14111328</td> 	<td>3743992.85888672</td></tr> 
<tr><td>10180921</td>	<td>10716600</td>	<td>12</td><td>    0.29754639</td> 	<td>      3.57055664</td> 	<td>3743996.42944336</td></tr> 
<tr><td>10716601</td>	<td>11252280</td>	<td>12</td><td>    0.14877319</td> 	<td>      1.78527832</td> 	<td>3743998.21472168</td></tr> 
<tr><td>11252281</td>	<td>11787960</td>	<td>12</td><td>    0.07438660</td> 	<td>      0.89263916</td> 	<td>3743999.10736084</td></tr> 
<tr><td>11787961</td>	<td>12323640</td>	<td>12</td><td>    0.03719330</td> 	<td>      0.44631958</td> 	<td>3743999.55368042</td></tr> 
<tr><td>12323641</td>	<td>12859320</td>	<td>12</td><td>    0.01859665</td> 	<td>      0.22315979</td> 	<td>3743999.77684021</td></tr> 
<tr><td>12859321</td>	<td>13395000</td>	<td>12</td><td>    0.00929832</td> 	<td>      0.11157990</td> 	<td>3743999.88842010</td></tr> 
<tr><td>13395001</td>	<td>13930680</td>	<td>12</td><td>    0.00464916</td> 	<td>      0.05578995</td> 	<td>3743999.94421005</td></tr> 
<tr><td>13930681</td>	<td>14466360</td>	<td>12</td><td>    0.00232458</td> 	<td>      0.02789497</td> 	<td>3743999.97210503</td></tr> 
<tr><td>14466361</td>	<td>15002040</td>	<td>12</td><td>    0.00116229</td> 	<td>      0.01394749</td> 	<td>3743999.98605251</td></tr> 
<tr><td>15002041</td>	<td>15537720</td>	<td>12</td><td>    0.00058115</td> 	<td>      0.00697374</td> 	<td>3743999.99302626</td></tr> 
<tr><td>15537721</td>	<td>16073400</td>	<td>12</td><td>    0.00029057</td> 	<td>      0.00348687</td> 	<td>3743999.99651313</td></tr> 
<tr><td>16073401</td>	<td>16609080</td>	<td>12</td><td>    0.00014529</td> 	<td>      0.00174344</td> 	<td>3743999.99825656</td></tr> 
<tr><td>16609081</td>	<td>17144760</td>	<td>12</td><td>    0.00007264</td> 	<td>      0.00087172</td> 	<td>3743999.99912828</td></tr> 
<tr><td>17144761</td>	<td>17680440</td>	<td>12</td><td>    0.00003632</td> 	<td>      0.00043586</td> 	<td>3743999.99956414</td></tr> 
<tr><td>17680441</td>	<td>18216120</td>	<td>12</td><td>    0.00001816</td> 	<td>      0.00021793</td> 	<td>3743999.99978207</td></tr> 
<tr><td>18216121</td>	<td>18751800</td>	<td>12</td><td>    0.00000908</td> 	<td>      0.00010896</td> 	<td>3743999.99989104</td></tr> 
<tr><td>18751801</td>	<td>19287480</td>	<td>12</td><td>    0.00000454</td> 	<td>      0.00005448</td> 	<td>3743999.99994552</td></tr> 
<tr><td>19287481</td>	<td>19823160</td>	<td>12</td><td>    0.00000227</td> 	<td>      0.00002724</td> 	<td>3743999.99997276</td></tr> 
<tr><td>19823161</td>	<td>20358840</td>	<td>12</td><td>    0.00000114</td> 	<td>      0.00001362</td> 	<td>3743999.99998638</td></tr> 
<tr><td>20358841</td>	<td>20894520</td>	<td>12</td><td>    0.00000057</td> 	<td>      0.00000681</td> 	<td>3743999.99999319</td></tr> 
<tr><td>20894521</td>	<td>21430200</td>	<td>12</td><td>    0.00000028</td> 	<td>      0.00000341</td> 	<td>3743999.99999660</td></tr> 
<tr><td>21430201</td>	<td>21965880</td>	<td>12</td><td>    0.00000014</td> 	<td>      0.00000170</td> 	<td>3743999.99999830</td></tr> 
<tr><td>21965881</td>	<td>22501560</td>	<td>12</td><td>    0.00000007</td> 	<td>      0.00000085</td> 	<td>3743999.99999915</td></tr> 
<tr><td>22501561</td>	<td>23037240</td>	<td>12</td><td>    0.00000004</td> 	<td>      0.00000043</td> 	<td>3743999.99999957</td></tr> 
<tr><td>23037241</td>	<td>23572920</td>	<td>12</td><td>    0.00000002</td> 	<td>      0.00000021</td> 	<td>3743999.99999979</td></tr> 
<tr><td>23572921</td>	<td>24108600</td>	<td>12</td><td>    0.00000001</td> 	<td>      0.00000011</td> 	<td>3743999.99999989</td></tr> 
<tr><td>24108601</td>	<td>     INF</td>	<td>12</td><td>    0.00000000</td> 	<td>      0.00000000</td> 	<td>3743999.99999989</td></tr>
<tr><td>Total	</td>	<td>        </td>	<td>  </td><td>              </td>	<td>3743999.99999989</td> 	<td>                </td></tr>
</table>
