<p align="center">
  <img src="banner.svg" alt="Tic-Tac-Toe" width="100%">
</p>

<p align="center">
  <span style="color:#7c3aed;"><strong>Python 3</strong></span>
  &nbsp;·&nbsp;
  <span style="color:#e11d48;"><strong>Player X</strong></span>
  &nbsp;·&nbsp;
  <span style="color:#0891b2;"><strong>Player O</strong></span>
  &nbsp;·&nbsp;
  <span style="color:#059669;"><strong>3×3 board</strong></span>
</p>

A two-player tic-tac-toe game in the terminal. Place your mark, block your opponent, and get three in a row.

<table>
  <tr>
    <td width="33%" style="background:#fff1f2; padding:16px 18px; border-radius:14px; border-top:5px solid #f43f5e; vertical-align:top;">
      <h3 style="color:#e11d48; margin:0 0 8px;">X goes first</h3>
      <p style="margin:0; color:#4c0519;">Type a square number from <strong>1</strong> to <strong>9</strong>. X always opens the game.</p>
    </td>
    <td width="33%" style="background:#ecfeff; padding:16px 18px; border-radius:14px; border-top:5px solid #06b6d4; vertical-align:top;">
      <h3 style="color:#0891b2; margin:0 0 8px;">O answers</h3>
      <p style="margin:0; color:#083344;">O plays second. Any empty square is fair game. Taken squares are rejected.</p>
    </td>
    <td width="33%" style="background:#f5f3ff; padding:16px 18px; border-radius:14px; border-top:5px solid #8b5cf6; vertical-align:top;">
      <h3 style="color:#6d28d9; margin:0 0 8px;">Win or draw</h3>
      <p style="margin:0; color:#2e1065;">Three in a row wins. A full board with no winner is a draw. Type <strong>y</strong> to play again.</p>
    </td>
  </tr>
</table>

## <span style="color:#6d28d9;">Play</span>

From this folder:

```powershell
python tictac.py
```

You need Python 3. No extra packages.

## <span style="color:#e11d48;">The board</span>

Empty squares show their numbers. After a move, the square shows <span style="color:#e11d48;"><strong>X</strong></span> or <span style="color:#0891b2;"><strong>O</strong></span>.

<table align="center" style="border-collapse:collapse; text-align:center; font-size:28px; font-weight:700; margin:12px auto;">
  <tr>
    <td style="width:72px; height:72px; border:4px solid #c4b5fd; color:#e11d48;">X</td>
    <td style="width:72px; height:72px; border:4px solid #c4b5fd; color:#94a3b8;">2</td>
    <td style="width:72px; height:72px; border:4px solid #c4b5fd; color:#0891b2;">O</td>
  </tr>
  <tr>
    <td style="width:72px; height:72px; border:4px solid #c4b5fd; color:#94a3b8;">4</td>
    <td style="width:72px; height:72px; border:4px solid #c4b5fd; color:#e11d48;">X</td>
    <td style="width:72px; height:72px; border:4px solid #c4b5fd; color:#94a3b8;">6</td>
  </tr>
  <tr>
    <td style="width:72px; height:72px; border:4px solid #c4b5fd; color:#94a3b8;">7</td>
    <td style="width:72px; height:72px; border:4px solid #c4b5fd; color:#0891b2;">O</td>
    <td style="width:72px; height:72px; border:4px solid #c4b5fd; color:#e11d48;">X</td>
  </tr>
</table>

<p align="center" style="color:#6d28d9;"><strong>X wins on the diagonal.</strong></p>

## <span style="color:#0891b2;">Rules</span>

| What happens | Result |
| --- | --- |
| Three in a row, column, or diagonal | That player wins |
| Every square is filled, nobody has three | Draw |
| A number outside 1–9, or a taken square | Ask again |
| Anything other than `y` at the end | Game quits |

## <span style="color:#059669;">Files</span>

| File | What it is |
| --- | --- |
| `tictac.py` | The game |
| `banner.svg` | The colored header above |
