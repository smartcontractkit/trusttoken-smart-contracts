## `LoanFactory2`

Deploy LoanTokens for pools created by PoolFactory, with this Contract


LoanTokens are deployed through a factory to ensure that all
LoanTokens adhere to the same contract code, rather than using an interface.

### `onlyAdmin()`






### `initialize(contract IPoolFactory _poolFactory, address _lender, address _liquidator, contract ICreditModel _creditModel, contract ITrueFiCreditOracle _creditOracle)` (external)



Initialize this contract and set currency token


### `setAdmin()` (external)





### `rate(contract ITrueFiPool2 pool, address borrower, uint256 amount) → uint256` (internal)






### `setCreditOracle(contract ITrueFiCreditOracle _creditOracle)` (external)





### `setCreditModel(contract ICreditModel _creditModel)` (external)






### `LoanTokenCreated(address contractAddress)`



Emitted when a LoanToken is created


### `CreditOracleChanged(contract ITrueFiCreditOracle creditOracle)`





### `CreditModelChanged(contract ICreditModel creditModel)`





