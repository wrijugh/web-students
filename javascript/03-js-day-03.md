# JavaScript - Day 3

Building simple Calculator

![Calculator](Calculator.png)

```javascript

<!-- JavaScript Section -->
<script>
    var result = ""

    function calculate(){
        var finalResult = eval(result);
        setResult(finalResult)
        result = '';
    }
    
    function buttonClick(n)
    {        
        result += n;
        //alert(result);
        setResult(result);        
    }

    function reset(){
        result = "";
        setResult(result);
    }

    function setResult(n){
        document.getElementById("txtResult").value = n;
    }
</script>
```

```html
<!-- HTML  -->
<h1>Simple Calculator</h1>

<style>
    td {
        text-align: center;
    }

</style>
<form id="form1">
    <table>
        <tr>
            <td colspan="4">
                <input type="text" id="txtResult" />
            </td>
        </tr>
        <tr>
            <td colspan="4">
                <input type="button" id="btnClear" value="   Clear   " onclick="reset()" />
            </td>
        </tr>
        <tr>
            <td>
                <input type="button" value="1" onclick="buttonClick(1)"  />
            </td>
            <td>
                <input type="button" value="2" onclick="buttonClick(2)" />
            </td>
            <td>
                <input type="button" value="3" onclick="buttonClick(3)" />
            </td>
            <td>
                <input type="button" value="+" onclick="buttonClick('+')" />
            </td>
        </tr>
        <tr>
            <td>
                <input type="button" value="4" onclick="buttonClick(4)" />
            </td>
            <td>
                <input type="button" value="5" onclick="buttonClick(5)" />
            </td>
            <td>
                <input type="button" value="6" onclick="buttonClick(6)" />
            </td>
            <td>
                <input type="button" value="-" onclick="buttonClick('-')" />
            </td>
        </tr>
        <tr>
            <td>
                <input type="button" value="7" onclick="buttonClick(7)" />
            </td>
            <td>
                <input type="button" value="8" onclick="buttonClick(8)" />
            </td>
            <td>
                <input type="button" value="9" onclick="buttonClick(9)" />
            </td>
            <td>
                <input type="button" value="*" onclick="buttonClick('*')" />
            </td>
        </tr>
        <tr>
            <td>
                <input type="button" value="0" onclick="buttonClick(0)" />
            </td>
            <td>
                <input type="button" value="." onclick="buttonClick('.')" />
            </td>
            <td>
                <input type="button" id="btnAddition" value="/" onclick="buttonClick('/')" />
            </td>
            <td>
                <input type="button" id="btnEqual" value="=" onclick="calculate()" />
            </td>
        </tr>

    </table>
</form>
```

## JavaScript Assignment #3

Build a calculator after practicing the abobe by yourself.

---

[Home](../README.md)

[Next: GitHub Day 1 >>](../github/00-github-day-01.md)