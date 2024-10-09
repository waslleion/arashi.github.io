<form id="vote-form">
  <input type="radio" name="vote" value="option1"> Option 1<br>
  <input type="radio" name="vote" value="option2"> Option 2<br>
  <button type="submit">投票する</button>
</form>

<script>
  document.getElementById('vote-form').addEventListener('submit', function(e) {
    e.preventDefault();
    // ユーザーの投票データを送信するコードを書く
    alert('投票が完了しました！');
  });
</script>
