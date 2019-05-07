# WebixReader

UIPATH机器人 webix 组件读取

Description
project extract from a webix table. (used by Bank of america, Huawei, Broadcom etc https://webix.com/)

The precondition/limitation of using this project are the following:

It only works with IE browser due to limitation of invoke js activity.
It assume there is only one webix table on one page. You could supply different view_id to the input parameter to extract multiple tables on one page.
Pivit table is not supported at the moment, but you could refactor to support it in case pivit table is used by your company. (https://webix.com/demos/pivot/ for example, doesn’t work)


To use this in your project, use the “get attribute” activity to get the view_id off the table container element.

