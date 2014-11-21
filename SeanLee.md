### Last week

* [STK]
  - '14、STK的窗口关闭为什么要加设定时器。' - In bug 832107 comment 2 mentioned, the previous menu without a STK_CMD_SELECT_ITEM or STK_CMD_SET_UP_MENU received can not be shown. 
  - Give a talk about STK
  - Issue from TCL: the TR of STK_RESULT_UICC_SESSION_TERM_BY_USER is sent at inappropriate time. I provide a patch to remove the related codes for the further verifivation.
  - Study the architecture of STK and find a way to fix the unexpected TR.
  - [WIP][bug 1093993] After providing the workaround patch for testing, the root cause is figured out. We are waiting the result of the further patch .
  - [WIP][bug 1094638] Similar root cause to bug 1093993.
  - [WIP][bug 1085248] Similar root cause to bug 1093993.

### This week

* [STK]
  - Keep fixing STK bugs.
  - Improve the handler of STK_CMD_GET_INPUT and STK_CMD_SET_UP_CALL command.
