# t(:enums)
t(:ENUMs_para)

## Side (`side`)
* `Buy`
* `Sell`

## Category(`category`)
* `linear` t(:dv3_category_linear)

## Symbol (`symbol`)
* `BTCUSDT`
* `ETHUSDT`
* `BNBUSDT`
* `ARBUSDT`
* `SOLUSDT`
* `BCHUSDT`
* `COMPUSDT`
* `MKRUSDT`
* `LTCUSDT`
* `XRPUSDT`
* `MATICUSDT`
* `SUIUSDT`
* `OPUSDT`
* `WLDUSDT`



t(:dv_enum_comment_getSymbol)

## Currency (`currency`/`coin`)
* `USDT`

## Contract Type(`contractType`)
* `LinearPerpetual`


## Contract Status(`status`)
* `Pending` t(:waiting_online)
* `Trading` t(:online)
* `Closed` t(:offline)

## Account type (`from_account_type`/`to_account_type`)
* `CONTRACT`  t(:accountType_contract)


## Wallet fund type (`walletFundType` / `type`)
* `Deposit` t(:deposit)
* `Withdraw` t(:withdraw)
* `RealisedPNL` t(:realisedpnl)
* `Commission` t(:commission)
* `Refund` t(:refund)




## Order type (`orderType`)
* `Limit` t(:limit)
* `Market` t(:market)

## Quantity (`qty`)
t(:quantity)

## Price (`price`)
t(:price)

## Time in force (`timeInForce`)
* `GoodTillCancel` t(:goodTillCancel)
* `ImmediateOrCancel` t(:immediateOrCancel)
* `FillOrKill` t(:fillOrKill)
* `PostOnly` t(:postOnly)

## Trigger price type (`triggerBy`)
* `LastPrice` t(:lastPrice)
* `IndexPrice` t(:indexPrice)
* `MarkPrice` t(:markPrice)

## Order (`order`)
t(:para_order)

* `desc` t(:desc)
* `asc` t(:asc)

## Order status (`orderStatus`/`stopOrderStatus`)
t(:para_orderStatusGet)

* `Created` t(:created1)
* `New` t(:new1)
* `Rejected` t(:rejected1)
* `PartiallyFilled` t(:partiallyFilled1)
* `Filled` t(:filled1)
* `PendingCancel` t(:pendingCancel1)
* `Cancelled` t(:cancelled1)

Only for conditional orders:

* `Untriggered` t(:untriggered)
* `Deactivated` t(:deactivated1)
* `Triggered` t(:triggered)
* `Active` t(:active)


## Cancel type (`cancelType`)
* `CancelByUser` t(:cancelByUser)
* `CancelByReduceOnly` t(:cancelByReduceOnly)
* `CancelByPrepareLiq`,`CancelAllBeforeLiq` t(:cancelByPrepareLiq)
* `CancelByPrepareAdl`,`CancelAllBeforeAdl` t(:cancelByPrepareAdl)
* `CancelByAdmin` t(:cancelByAdmin)
* `CancelByTpSlTsClear` t(:cancelByTpSlTsClear)
* `CancelByPzSideCh` t(:cancelByPzSideCh)

## Create type (`createType`)
* `CreateByUser`
* `CreateByClosing`
* `CreateByAdminClosing`
* `CreateByStopOrder`
* `CreateByTakeProfit`
* `CreateByStopLoss`
* `CreateByTrailingStop`
* `CreateByLiq` - Created by partial liquidation
* `CreateByAdl_PassThrough` - Created by ADL
* `CreateByTakeOver_PassThrough` - Created by liquidation takeover

## Exec type (`execType`)
* `Trade` t(:exec_trade)
* `AdlTrade` t(:exec_adlTrade)
* `Funding` t(:exec_funding)
* `BustTrade` t(:exec_bustTrade)

## Liquidity type (`lastLiquidityInd`)
* `AddedLiquidity` t(:addedLiquidity)
* `RemovedLiquidity` t(:removedLiquidity)


## Tick direction type (`tickDirection`)
t(:tick_direction)

* `PlusTick` t(:plusTick)
* `ZeroPlusTick` t(:zeroPlusTick)
* `MinusTick` t(:minusTick)
* `ZeroMinusTick` t(:zeroMinusTick)

## TP/SL mode (`tpSlMode`)
t(:tp_sl_mode)

* `Full` t(:Full)
* `Partial` t(:Partial)

## Kline interval (`interval`)
* `1` t(:interval_1)
* `3` t(:interval_3)
* `5` t(:interval_5)
* `15` t(:interval_15)
* `30` t(:interval_30)
* `60` t(:interval_60)
* `120` t(:interval_120)
* `240` t(:interval_240)
* `360` t(:interval_360)
* `720` t(:interval_720)
* `D` t(:interval_D)
* `W` t(:interval_W)
* `M` t(:interval_M)

## Date (`startDate`/`endDate`)
t(:date)

## Stop order type (`stopOrderType`)
* `TakeProfit`
* `StopLoss`
* `TrailingStop`
* `Stop`

## Transaction-Log Type (`type`)
* `TRANSFER_IN` t(:transfer_in)
* `TRANSFER_OUT` t(:transfer_out)
* `TRADE` t(:trade)
* `SETTLEMENT` t(:settlement)
* `DELIEVRY` t(:delivery)
* `LIQUIDATION` t(:liquidation)
* `INSURANCE_FUND` t(:insurance_fund)
* `FEE_REFUND` t(:fee_refund)
* `INTEREST` t(:interest)
* `BONUS` t(:bonusEnum)
* `CURRENCY_SELL` t(:currencySell)
* `CURRENCY_BUY` t(:currencyBuy)

## Order Filter (`orderFilter`)
* `Order`
* `StopOrder`

## Upgrade Result (`result`)
* `Processing`
* `Successfully upgraded`
* `Upgrade failed`
* `Rejected`
