# Why is Wanchain using SMPC instead of Mullti-signature ?


Multi-signature and MPC are both used for managing account with multiple parties. MPC has several benefits over mutli-signature

1. __More generic.__ Muti-signature is always done through smart contract or spv script. This limits its range of application as the underlying infrastructure has to have some kind of scripting support. Wanchain’s MPC method can adjust almost to any blockchain architectures no matter whether they support smart contract or not.

2. __Less storage cost.__ Suppose there are N parties controlling an account. To send a transaction from this account, about N signatures need to be attached to the transaction when using multi-signature. But using Wanchian’s MPC method, only one signature is required in the transaction, the same as a normal transaction. MPC is a process of cryptographic signature aggregation. With Wanchain’s MPC method, participants locally generate signature shares and then compute their aggregation. Only the final signature is attached in the transaction.

3. __Lower transaction fee.__ Muti-signature has a larger storage cost, also the verification process needs more computation compared to Wanchian’s MPC. So Wanchain’s MPC naturally incurs lower transaction fee.

__In summary, MPC is more general and has less storage cost and lower transaction fee. So Wanchain chose it for its cross-chain design.__
