<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tic Tac Toe</title>
  <style>
    .game-board {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-gap: 10px;
      width: 300px;
      margin: 20px auto;
    }

    .game-cell {
      width: 100px;
      height: 100px;
      background-color: #f1f1f1;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 48px;
      font-weight: bold;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="game-board">
    <div class="game-cell"></div>
    <div class="game-cell"></div>
    <div class="game-cell"></div>
    <div class="game-cell"></div>
    <div class="game-cell"></div>
    <div class="game-cell"></div>
    <div class="game-cell"></div>
    <div class="game-cell"></div>
