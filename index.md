<script src="https://cdn.jsdelivr.net/npm/jquery@3.6.0/dist/jquery.min.js"></script>
<script>
  $(function() {
    console.log('hello');
    
    $.get('./mocks/welfare.json', function(ret) {
      console.log(ret);
    });
  });
</script>
