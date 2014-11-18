### Last week

* [STK]
  - Improve the handler of STK_CMD_GET_INPUT and STK_CMD_SET_UP_CALL command.
  - [bug 1094638] The unexpected TR is resolved. The get_input dialog should not be shown if there is a call from another SIM. We need to discuss with TCL if this is defined in specification.
  - The patches of the following 4 bugs are provided to TCL for LAB test.
   - [bug 1088611] Provide the patch merged from bug 1091483 and my solution to TCL. Wait for their result.
   - [bug 1093993] The patch is PASS for TCL LAB test.
   - [bug 1085248] The unexpected TR is resolved, but refresh reset command is incorrect. Shawn Ku helps to study if it is a Gecko issue.
   - [bug 1033974] Remove the unnecessary TR of STK_CMD_SEND_SS/STK_CMD_SEND_USSD/STK_CMD_SEND_SMS/STK_CMD_SEND_DTMF.

### This week

* [STK]
  - [bug 1100201] Create a meta bug for STK improvement.
  - [bug 1100218] [STK] Use IAC instead of mozSettings to transfer data between System app and Settings app
