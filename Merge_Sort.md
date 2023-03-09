<h1 align="center" >Merge Sort Aşamaları</h1>

<table align="center" border="1">
    <thead>
        <tr>
            <th >Başlangıç</th>
            <th colspan = 6>16 , 21 , 11 , 8 , 12 , 22</th>
        </tr>
    </thead>
    <tbody  align="center">
        <tr>
            <td >1. Adım</td>
            <td colspan=3>16 , 21 , 11</td>
            <td colspan=3>8 , 12 , 22</td>
        </tr>
        <tr>
            <td >2. Adım</td>
            <td colspan=1>16</td>
            <td colspan=2>21 , 11</td>
            <td colspan=2>8 , 12 </td>
            <td colspan=1>22</td>
        </tr>
        <tr>
            <td >3. Adım</td>
            <td >16</td>
            <td >21</td>
            <td >11</td>
            <td >8</td>
            <td >12</td>
            <td >22</td>
        </tr>
        <tr>
            <td >4. Adım</td>
            <td colspan=1>16</td>
            <td colspan=2>11 , 21</td>
            <td colspan=2>8 , 12 </td>
            <td colspan=1>22</td>
        </tr>
        <tr>
            <td >5. Adım</td>
            <td colspan=3>11 , 16 , 21</td>
            <td colspan=3>8 , 12 , 22</td>
        </tr>
        <tr>
            <th >6. Adım</td>
            <th colspan=6>8 , 11 , 12 , 16 , 21 , 22</td>
        </tr>
    </tbody>
</table>

<h1 align="center" >Big-O Gösterimi</h1>
<h3 align="center" >O(nlogn)</h3>

