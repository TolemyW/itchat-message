2019/04/12 16:58:06:**吴家宝** : 我在日志里面找，数组越界的报错是这个sql的一个task报的
*************************************************************************************
2019/04/12 17:00:23:**吴家宝** : 你看看里面的表的表结构中的数据类型是不是能对上
*************************************************************************************
2019/04/12 17:00:36:**吴家宝** : 有没有把string转int或decima的情况出现
*************************************************************************************
2019/04/12 17:03:18:**喂喂** : 恩。我可以问下。
*************************************************************************************
2019/04/12 17:03:44:**吴家宝** : insert into hdm.T_HDM_HZ_CON_CONTRACT_CASHFLOW (ACCUMULATED_UNPAID_INTEREST, ACCUMULATED_UNPD_INT_TAX_INCL, ALERT_SCHEME, BEGINNING_OF_LEASE_YEAR, BILLING_AMOUNT, BILLING_INTEREST, BILLING_PRINCIPAL, BILLING_STATUS, CALC_DATE, CALC_LINE_ID, CASHFLOW_EXTEND_ID, CASHFLOW_ID, CF_DIRECTION, CF_ITEM, CF_STATUS, CF_TYPE, COLOUR_SCHEME, CONTRACT_ID, CREATE_DEBTS_REVERSE_JE_FLAG, CREATED_BY, CREATION_DATE, DEDUCTION_AMOUNT, DEDUCTION_FLAG, DISCOUNTING_DAYS, DUE_AMOUNT, DUE_AMOUNT_CNY, DUE_AMOUNT_FUNC, DUE_DATE, EQUAL_FLAG, EXCHANGE_RATE, EXCHANGE_RATE_QUOTATION, EXCHANGE_RATE_TYPE, FIN_INCOME_DATE, FINANCING_COST, FIX_PRINCIPAL_FLAG, FIX_RENTAL_FLAG, FULL_WRITE_OFF_DATE, GENERATED_SOURCE, GENERATED_SOURCE_DOC_ID, IN_FLAG, INT_RATE, INTEREST, INTEREST_ACCRUAL_BAL_TAX_INCL, INTEREST_ACCRUAL_BALANCE, INTEREST_CNY, INTEREST_EQ_PRIN_ADJ, INTEREST_EQ_PRIN_RAW, INTEREST_EQ_PYMT_ADJ, INTEREST_EQ_PYMT_RAW, INTEREST_IMPLICIT_RATE, INTEREST_ONLY_FLAG, INTEREST_PERIOD_DAYS, LAST_RECEIVED_DATE, LAST_UPDATE_DATE, LAST_UPDATED_BY, LEASE_YEAR, LN_USER_COL_D01, LN_USER_COL_D02, LN_USER_COL_D03, LN_USER_COL_D04, LN_USER_COL_D05, LN_USER_COL_N01, LN_USER_COL_N02, LN_USER_COL_N03, LN_USER_COL_N04, LN_USER_COL_N05, LN_USER_COL_N06, LN_USER_COL_N07, LN_USER_COL_N08, LN_USER_COL_N09, LN_USER_COL_N10, LN_USER_COL_N11, LN_USER_COL_N12, LN_USER_COL_N13, LN_USER_COL_N14, LN_USER_COL_N15, LN_USER_COL_N16, LN_USER_COL_N17, LN_USER_COL_N18, LN_USER_COL_N19, LN_USER_COL_N20, LN_USER_COL_V01, LN_USER_COL_V02, LN_USER_COL_V03, LN_USER_COL_V04, LN_USER_COL_V05, MAIN_BUSINESS_COST, MAIN_BUSINESS_INCOME, MANUAL_FLAG, NET_DUE_AMOUNT, NET_INTEREST, NET_INTEREST_IMPLICIT, NET_PRINCIPAL, NET_PRINCIPAL_IMPLICIT, OUT_FLAG, OUTSTANDING_INT_TAX_INCLD, OUTSTANDING_INTEREST, OUTSTANDING_PRIN_TAX_INCLD, OUTSTANDING_PRINCIPAL, OUTSTANDING_RENTAL, OUTSTANDING_RENTAL_TAX_INCLD, OVERDUE_AMOUNT, OVERDUE_BOOK_DATE, OVERDUE_INTEREST, OVERDUE_MAX_DAYS, OVERDUE_PRINCIPAL, OVERDUE_REMARK, OVERDUE_STATUS, PAYMENT_METHOD_CODE, PENALTY_PROCESS_STATUS, PERIOD_NUM, PRINCIPAL, PRINC
*************************************************************************************
2019/04/12 17:03:50:**吴家宝** : 图片发不出去，我就发文本了😂
*************************************************************************************
2019/04/12 17:04:04:**喂喂** : 好。
*************************************************************************************
2019/04/12 17:08:20:**喂喂** : [点我进附件](https://github.com/CorkiZhang/itchat-message/tree/master/sla2-824海尔融资inceptor 4040报错无法显/ATTACHMENT/hive-server2.log)
*******************************************************************************
2019/04/12 17:09:09:**吴家宝** : 压缩一下😂
*************************************************************************************
2019/04/12 17:09:45:**喂喂** : 传完了。这里面有个OOM报错：PermGen space
*************************************************************************************
2019/04/12 17:10:01:**吴家宝** : 几点几的版本
*************************************************************************************
2019/04/12 17:10:07:**喂喂** : 5.2.2
*************************************************************************************
