# gsitm
목표
1. html만을 이용해서 게시판을 구현한다.
2. 저장소는 local storage를 활용한다.
3. 읽기, 쓰기, 수정, 삭제를 구현한다.

활용기술
1. html
2. css
3. javascript

조원

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
<style>
    td, th{border:solid 1px;}
    table {
        border-collapse:collapse;
        }
</style>
</head>
<body>
    <table style="width:100%;border:solid 1px;">
        <tr>
          <th>No</th>
          <th>Title</th>
          <th>Whiter</th>
        </tr>
        <tr>
          <td>Jill</td>
          <td>Smith</td>
          <td>50</td>
        </tr>
        <tr>
          <td>Eve</td>
          <td>Jackson</td>
          <td>94</td>
        </tr>
      </table>

<h4 style="color:red">This is a Heading</h1>
<p style="color:blue">This is a paragraph.</p>
<a href="javascript:movew3school()">This is a link</a>
<br/>
<br/>
<br/>
<form method="post" action="view.html">
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname">
    <input type="submit" value="전송">
  </form>
<img src="https://cdn.pixabay.com/photo/2021/08/06/18/46/dog-6526980_960_720.jpg" alt="W3Schools.com" width="104" height="142">
<p>
    This paragraph<br/>
    contains a lot of lines<br/>
    in the source code,<br/>
    but the browser<br/>
    ignores it.<br/>
    </p>
    
    <p>
    This paragraph<br/>
    contains         a lot of spaces<br/>
    in the source         code,<br/>
    but the        browser<br/>
    ignores it.<br/>
    </p>
   
    
</body>
<script>
    function movew3school () {
        window.location.href = "https://www.w3schools.com";
    }
</script>
</html>
