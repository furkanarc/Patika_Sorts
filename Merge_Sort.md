## Merge Sort Aşamaları

<table >
    <thead>
        <tr>
            <th >Başlangıç</th>
            <th colspan = 6>16 , 21 , 11 , 8 , 12 , 22</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">1. Adım</td>
            <td align="center" colspan=3>16 , 21 , 11</td>
            <td align="center" colspan=3>8 , 12 , 22</td>
        </tr>
        <tr>
            <td align="center">2. Adım</td>
            <td colspan=1>16</td>
            <td align="center" colspan=2>21 , 11</td>
            <td align="center" colspan=2>8 , 12 </td>
            <td colspan=1>22</td>
        </tr>
        <tr>
            <td align="center" colspan=1>3. Adım</td>
            <td colspan=1>16</td>
            <td colspan=1>21</td>
            <td colspan=1>11</td>
            <td colspan=1>8</td>
            <td colspan=1>12</td>
            <td colspan=1>22</td>
        </tr>
        <tr>
            <td align="center">4. Adım</td>
            <td colspan=1>16</td>
            <td align="center" colspan=2>11 , 21</td>
            <td align="center" colspan=2>8 , 12 </td>
            <td colspan=1>22</td>
        </tr>
        <tr>
            <td align="center">5. Adım</td>
            <td align="center" colspan=3>11 , 16 , 21</td>
            <td align="center" colspan=3>8 , 12 , 22</td>
        </tr>
        <tr>
            <td align="center">6. Adım</td>
            <td align="center" colspan = 6>8 , 11 , 12 , 16 , 21 , 22</td>
        </tr>
        <tr>
            <th >Bitiş</th>
            <th colspan = 6>8 , 11 , 12 , 16 , 21 , 22</th>
        </tr>
    </tbody>
</table>

## Big-O Gösterimi
### O(nlogn)
