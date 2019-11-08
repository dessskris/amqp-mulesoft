MuleSoft project to demonstrate how to connect to AMQP 0-9-1

Please change the AMQP connection to your own. You can create a free account on https://cloudamqp.com

Set up the following queues:
* CAKE_ORDER
* HOT_BEVERAGE_ORDER
* ORDER_STATUS

Set up the following direct exchange:
* ORDER

Set up the following bindings:

| Queue              | Routing Key      |
|--------------------|------------------|
| CAKE_ORDER         | cakeOrder        |
| HOT_BEVERAGE_ORDER | hotBeverageOrder |
| ORDER_STATUS       | orderStatus      |

Please refer to slides on https://slides.com/dessskris/amqp-mulesoft
