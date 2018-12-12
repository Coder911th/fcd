  <template> 
    <div class="counter">
      <button class="minus">-</button>
      <input  value="1" min="1" type="number" disabled/>
      <button class="plus">+</button>
    </div>
  </template>

  <script>
	export default {};
  </script>

  <style>
	body {
	  font-size: 52px;
	  font-family: "Monaco", "Courier", monospace;
	}

	input { 
	  border: none;
	  width:50px;
	  text-align: center;
	  color: #1FA19C; 
	  background-color: white; 
	}

	button{
	  background-color: #1FA19C; 
	  color: white; 
	  border-radius: 4px;
	  width:25px;
	  height:22px;
	}body {
	  font-size: 52px;
	  font-family: "Monaco", "Courier", monospace;
	}

	input { 
	  border: none;
	  width:50px;
	  text-align: center;
	  color: #1FA19C; 
	  background-color: white; 
	}

	button{
	  background-color: #1FA19C; 
	  color: white; 
	  border-radius: 4px;
	  width:25px;
	  height:22px;
}
  </style>
