# Blockchain_Module4_Challenge

### Evaluation Evidence 
Compilation screenshots for KaiseiCoin contract
![markdown_image](Evidence_screenshots/KaiseiCoin_compilation_screen.png)

Compilation screenshot for KaiseiCoinCrowdsale contract
![markdown_image](Evidence_screenshots/KaiseiCoinCrowdsale_compilation_screen.png)

### Deployment Procedure
1. Deploy KaseiCoinCrowdsaleDeployer contract with Name, Symbol and Wallet
![markdown_image](Evidence_screenshots/Deploy_Step1_KaseiCoinCrowdsaleDeployer.png)

2. Confirm in the MetaMask wallet
![markdown_image](Evidence_screenshots/Deploy_Step2_MetaMask_Confirmation.png)

3. In the deployed KaseiCoinCrowdsaleDeployer, copy the kasei_crowdsale_address, and switch to KaseiCoinCrowdsale contract by ticking At Address to deploy KaseiCoinCrowdsale contract
![markdown_image](Evidence_screenshots/Deploy_Step3_KaseiCoinCrowdsale.png)

4. In the deployed KaseiCoinCrowdsaleDeployer, copy the kasei_token_address, and switch to KaseiCoin contract by ticking At Address to deploy the KaseiCoin contract
![markdown_image](Evidence_screenshots/Deploy_Step4_KaseiCoin.png)

### Test Results
1. In the first transaction, I set up 1000 wei in the value and ticked the buyTokens as following, which generated weiRaised 1000 in the KaserCoinCrowdsale contract.
![markdown_image](Evidence_screenshots/Deploy_Test1_buyToken.png)

Also checked the balanceOf = 1000 and totalSupply = 1000 in the KaserCoin contract
![markdown_image](Evidence_screenshots/Deploy_Test1_balanceOf.png)

2. In the second transaction, I set up 500 wei in the value and ticked the buyTokens again.
![markdown_image](Evidence_screenshots/Deploy_Test2_Second_buyToken.png)

The weiRaised in total will be 1500 (including 1000+ 500) as expected
![markdown_image](Evidence_screenshots/Deploy_Test2_weiRaised_in_total.png)

