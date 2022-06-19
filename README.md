# ERC20Token

功能包含：分红，回流，营销钱包，黑名单，销毁，增发，暂停交易等
临时索池子，用粉红平台；永久索就是把LP打进黑洞

NAME_:代币全名,如Dogecoin Token

SYMBOL_:代币符号，如BTC

TOTALSUPPLY_:发行量，如1000000

ADDRS:reward, router, marketing wallet, dividendTracker，如
["0x7a8BE15270Ef0d1319b898267d7480d5f390e119","0x9ac64cc6e4415144c455bd8e4837fea55603e5c3","0xac109C8025F272414fd9e2faA805a583708A017f","0xaf220fea3550d2cb7ec0a489046f977b3e007329"]

BUYFEESETTING_:例 [1,2,3,4] 数字之和不能超过25

    buyTokenRewardsFee 分红代币
    buyLiquidityFee 添加流动性
    buyMarketingFee 打入营销钱包
    buyDeadFee 销毁，打入黑洞地址
SELLFEESETTING_:例 [2,2,3,4] 数字之和不能超过25
TOKENBALANCEFORREWARD_:最小持仓分红数量，整数
SERVICEFEERECEIVER_:依赖合约0xba4250dc317D70C9DFEc87F326F022D902FCc5FF
SERVICEFEE_:100

# ADDRS
1. 分红代币地址
2. Swap路由地址
3. 你的营销钱包地址
4. 随便写一个地址，deploy的时候会自动生成

# BSC Testnet
DOGE合约 0x7a8BE15270Ef0d1319b898267d7480d5f390e119
ETH合约 0x8babbb98678facc7342735486c851abd7a0d17ca
测试WBNB合约：0xae13d989dac2f0debff460ac112a837c89baa7cd
测试网pancakeswap路由地址:0x9ac64cc6e4415144c455bd8e4837fea55603e5c3

["0x7a8BE15270Ef0d1319b898267d7480d5f390e119","0x9ac64cc6e4415144c455bd8e4837fea55603e5c3","0xac109C8025F272414fd9e2faA805a583708A017f","0xaf220fea3550d2cb7ec0a489046f977b3e007329"]

分红swap交易参考 https://testnet.bscscan.com/tx/0x29ae754e6a53886e77c1d22d873ad82e344c3494349fdd3fe7e1692c4e044627


# BSC main net
DOGE 0xba2ae424d960c26247dd6c32edc70b295c744c43
1、DOGEpair 0xac109C8025F272414fd9e2faA805a583708A017f
2、PancakeRouter 0x10ED43C718714eb63d5aA57B78B54704E256024E
3、营销地址 0x436a6D1392e14734936143607400E44C0A11D6F2
4、dividendTracker 随意填，会自动生成追踪合约
["0xba2ae424d960c26247dd6c32edc70b295c744c43","0x10ED43C718714eb63d5aA57B78B54704E256024E","0x436a6D1392e14734936143607400E44C0A11D6F2","0xaf220fea3550d2cb7ec0a489046f977b3e007329"]



# Polygon Shib
Shib 0x6f8a06447Ff6FcF75d803135a7de15CE88C1d4ec
Shib路由 0x5FB641De2663e8a94C9dea0a539817850d996e99
Quickswap Router 0xa5E0829CaCEd8fFDD4De3c43696c57F7D7A678ff
营销地址 0x436a6D1392e14734936143607400E44C0A11D6F2
["0x6f8a06447Ff6FcF75d803135a7de15CE88C1d4ec","0xa5E0829CaCEd8fFDD4De3c43696c57F7D7A678ff","0x436a6D1392e14734936143607400E44C0A11D6F2","0xaf220fea3550d2cb7ec0a489046f977b3e007329"]



# BSC测试网络：
名称：BSC Testnet
RPC：https://data-seed-prebsc-1-s1.binance.org:8545/
链ID：97
货币符号：tBNB
区块链浏览器：https://testnet.bscscan.com
pancake-测试地址：https://pancake.kiemtienonline360.com/#/swap
BSC测试网各种合约：https://bsc.kiemtienonline360.com/
测试网领取BNB：https://testnet.binance.org/faucet-smart
DOGE合约：0x7a8BE15270Ef0d1319b898267d7480d5f390e119
测试路由地址:0x9ac64cc6e4415144c455bd8e4837fea55603e5c3
测试WBNB合约：0xae13d989dac2f0debff460ac112a837c89baa7cd

