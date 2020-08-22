# html-table-converter

Custom _HttpMessageConverter_ to convert simple HTML table to a String representation.

**Endpoint:**
http://localhost:8080/table/add

**Sample RequestBody - use HTML code:**
<table>
    <thead>
        <tr>
            <th>Items</th>
            <th>Expenditure</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Stationary</td>
            <td>2,000</td>
        </tr>
        <tr>
            <td>Furniture</td>
            <td>10,000</td>
        </tr>        
    </tbody>
    <tfoot>
        <tr>
            <th>Total</th>
            <td>12,000</td>
        </tr>
    </tfoot>
</table>
