<h1> Creating a Custom Balance Table for your Pavlov VR Dedicated Server </h1>

1. Sign up with github: https://github.com/join

2. Fork the repository from: https://github.com/vankruptgames/BalancingTable

![Image of Guide1](https://github.com/juntistik/BalancingTable/Guide/BTG01.png)

3. Once you've forked the repository you will be brought to the repositories page, click on BalancingTable.csv.

![Image of Guide2](https://github.com/juntistik/BalancingTable/Guide/BTG02.png)

4. This is the file that will be fetched by the servers when the map loads. You can edit it by clicking on it then selecting the pencil in the top right. You can also can download it, edit it via google docs or any other spreadsheet program and reupload it to your forked repository.

![Image of Guide3](https://github.com/juntistik/BalancingTable/Guide/BTG03.png)

5. To specify this file on the server you will need a portion of the link to the file, you can find this by clicking on the BalancingTable.csv in your repository, then clicking "Raw" in the top right.

![Image of Guide4](https://github.com/juntistik/BalancingTable/Guide/BTG04.png)

6. Then copy the portion of the link between raw.githubusercontent.com/ and /BalancingTable.csv (example. "Mark-Dey/BalancingTable/main")

![Image of Guide5](https://github.com/juntistik/BalancingTable/Guide/BTG05.png)

You will specify this in your Game.ini with: `BalanceTableURL="vankruptgames/BalancingTable/main/"`

Any changes to your forked balance table on github will be loaded on map start, if you run into any issues loading the balance table check the logs on server startup for warnings.
