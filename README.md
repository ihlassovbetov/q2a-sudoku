# q2a-sudoku

<b>Plugin Name:</b>  Q2A Sudoku <br>
<b>Price:</b> 30 USD (contact me to buy) <br>
<b>Plugin Description:</b> This is a sudoku game designed for Q2A platforms. It is a premium paid plugin. It adds a game page and a sudoku user ranking page. In the game, there is error count, hint count, reset count, and timer. Moreover, it has marking, deleting, using hints, and printing functionalities.  <br>
<br>
<ul class="first">
	<b>SUDOKU GAME PAGE:</b>
	<li>General:
		<ul class="second">
			<li>The sudoku board is 9x9. In total 81 cells.</li>
      <li>There will be a button link to the Sudoku User Ranking Page.</li>
		</ul>
	</li>
  <br/>
  <li>Difficulty Level:
		<ul class="second">
			<li>Easy: Initially 35 numbers will be given out of 81.</li>
			<li>Medium: Initially 30 numbers will be given out of 81.</li>
      <li>Hard: Initially 25 numbers will be given out of 81.</li>
		</ul>
	</li>
  <br/>
  <li>Stats/Counts:
		<ul class="second">
			<li>Errors Count: it will count errors made by the user.</li>
      <li>Hints Count: it will count hints used by the user.</li>
      <li>Resets Count: it will count resets made by the user.</li>
      <li>Timer: it will show time elapsed in minutes and seconds.</li>
		</ul>
	</li>
  <br/>
<li>Functions/Buttons:
		<ul class="second">
			<li>TIMER: it has 2 modes: Pause and Play. Initially, it automatically starts the time and it is in play mode. User can anytime pause the game. But when it is paused, the sudoku board will be cencored, so that users cannot continue game without timer. Unpausing the game, will again bring the board and last saved numbers.</li>
      <li>MARKING (ON/OFF): when it is clicked, it turns ON and the game board will be on MARKING/NOTING mode.</li>
			<li>DELETE: when it is clicked, it will delete the user inputted number at the active cell on the game board.</li>
      <li>HINT: when it is clicked, it will give correct number for the active cell on the game board, and it will be fixed, non-deletable. Hint count will increase by 1 each time.</li>
      <li>PRINT: when it is clicked, it will pop up print window for the sudoku page.</li>
      <li>NEW GAME: it starts a new sudoku game with selected difficulty level. All counts will be reset.</li>
      <li>RESET: it resets current sudoku game. All counts will be reset. But after reset the game will be at training mode. It wont be considered for sudoku user ranking.</li>
		</ul>
	</li>
</ul>	
<br/>
<ul class="first">	
	<b>HOW SCORE IS CALCULATED?</b>
	<li>It is custom strategy of calculation. It can be improved or changed. Here, we calculate the COST of completing the game. The parameters of this Cost is minutes spent, seconds spent, errors made, hints used. And it is calculated as below.</li>
	<li>COST: Minutes + Seconds/60 + Errors*5 + Hints*10</li>
	<li>Each difficulty level has its own maximum score. So, user's score will be Max.Score minus Cost.</li>
	<li>SCORE: Maximum Score - Cost</li>
  <li>Max.Score in Hard. level is 300.</li>
</ul>
<br/>
<ul class="first">	
	<b>SUDOKU USER RANKING PAGE:</b>
	<li>There will be 3 table ranking for each levels: Easy, Medium, Hard.</li>
	<li>Max.Score in Easy level is 100.</li>
	<li>Max.Score in Medium level is 200.</li>
  <li>Max.Score in Hard. level is 300.</li>
</ul>
<br/>
<ul class="first">	
	<b>Plugin Admin Settings:</b>
	<li>Admin should enable the plugin. And it will ask to setup database table for it. Admin should initialize setup.</li>
</ul>
<br/>
<ul class="first">	
	<b>TEST DEMO WEBSITE: <a href="https://q2a-demo.gyzgyn.com/sudoku" target="_blank">LIVE DEMO</a></b>
	<li>Standard registered user (username: deneme_11 / pass: test1234)</li>
	<li><img src="https://ihlassovbetov.github.io/assets/plugin-ss/sudoku/sudoku-1.png" width="400px" height="auto" /></li>
	<li><img src="https://ihlassovbetov.github.io/assets/plugin-ss/sudoku/sudoku-2.png" width="400px" height="auto" /></li>
	<li><img src="https://ihlassovbetov.github.io/assets/plugin-ss/sudoku/sudoku-3.png" width="400px" height="auto" /></li>
	<li><img src="https://ihlassovbetov.github.io/assets/plugin-ss/sudoku/sudoku-4.png" width="400px" height="auto" /></li>
	<li><img src="https://ihlassovbetov.github.io/assets/plugin-ss/sudoku/sudoku-5.png" width="400px" height="auto" /></li>
	<li><img src="https://ihlassovbetov.github.io/assets/plugin-ss/sudoku/sudoku-6.png" width="400px" height="auto" /></li>
</ul>
