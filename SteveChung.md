## This week 2/20 ~ 3/3
* Autofill
    - [Bug 1339007](https://bugzilla.mozilla.org/show_bug.cgi?id=1339007) - Replace async getEnabledStatus with initialProcessData for content process init
        - Landed
    - [Bug 1338420](https://bugzilla.mozilla.org/show_bug.cgi?id=1338420) - Fallback to form history if whole profiles doesn't have any data for the specific fields
        - r? . Decided to switch the search instance dynamically instead of creating another API for search fall back per MattN's suggestion.
    - [Bug 1338482](https://bugzilla.mozilla.org/show_bug.cgi?id=1338482) - Fallback to form history if the target field doesn't have data in selected profile
        - r? . The solution is based on Bug 1338420
* Devtool:
    - N/A
