# Milestone Delivery :mailbox:

**The invoice has been send out correctly for this milestone and the delivery is according to the official [milestone delivery guidelines](https://github.com/smart-contract-bounty/Support-Docs/blob/master/milestone-deliverables-guidelines.md).**  

* **Application Document:** [Starlay Finance](https://github.com/Chidasan/Ecosystem-Grants/blob/master/applications/starlay_finance.md).

**Deliverables**

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 0a. | License | [License](https://github.com/starlay-finance/starlay-protocol-wasm/blob/8fc7fa89b5be0651abe9287c69156b1690af3845/LICENSE.md) | 　|
| 0b. | Documentation | [Documentation](https://docs.starlay.finance) |　 |
| **1.** | Repay_all function | [Repay_all function](https://github.com/starlay-finance/starlay-protocol-wasm/blob/8fc7fa89b5be0651abe9287c69156b1690af3845/logics/impls/pool/mod.rs#L418) | **Test link:** [Repay_all](https://github.com/starlay-finance/starlay-protocol-wasm/blob/8fc7fa89b5be0651abe9287c69156b1690af3845/tests/Pool1.spec.ts#L662) **Test Method:** 1. Run swanky-node on localhost 2. yarn compile 3. yarn test:single tests/Pool1.spec.ts |
| **2.** | Redeem_all function | [Redeem_all function](https://github.com/starlay-finance/starlay-protocol-wasm/blob/8fc7fa89b5be0651abe9287c69156b1690af3845/logics/impls/pool/mod.rs#L384) | **Test link:** [Redeem_all](https://github.com/starlay-finance/starlay-protocol-wasm/blob/8fc7fa89b5be0651abe9287c69156b1690af3845/tests/Pool1.spec.ts#L361) **Test Method:** 1. Run swanky-node on localhost 2. yarn compile 3. yarn test:single tests/Pool1.spec.ts |
| **3.** | Flashloan function| [Flashloan function](https://github.com/starlay-finance/starlay-protocol-wasm/blob/8fc7fa89b5be0651abe9287c69156b1690af3845/logics/impls/flashloan_gateway.rs#L54) | **Test link:** [Flashloan](https://github.com/starlay-finance/starlay-protocol-wasm/blob/8fc7fa89b5be0651abe9287c69156b1690af3845/tests/Flashloan.spec.ts) **Test Method:** 1. Run swanky-node on localhost 2. yarn compile 3. yarn test:single tests/Flashloan.spec.ts |
| **4.** | Mobile support| [Mobile support](https://testnet-wasm.starlay.finance/) |  |

**Additional Information**
* Post-audit refinement will be addressed after the audit is completed. 
* We've updated the flashloan part on our gitbook. Also we've been updating and modifying other sections on the following the Notion page. As disucussed in the milestone1-1, once we transition to the mainnet, we will promptly update our gitbook page with the relevant information and resources. https://unruly-innovation-bff.notion.site/Starlay-Gitbook-5a9fd96d676a47fdbd411c07e0857f9e?pvs=4