function dailyLog226() {
  const downloads = [120, 145, 98, 170, 132, 160, 115];

  const total = downloads.reduce((sum, count) => sum + count, 0);
  const average = total / downloads.length;
  const highest = Math.max(...downloads);

  console.log("Daily Download Report");
  console.log("---------------------");
  console.log(`Total Downloads: ${total}`);
  console.log(`Average Downloads: ${average.toFixed(2)}`);
  console.log(`Highest Downloads: ${highest}`);
}

dailyLog226();
