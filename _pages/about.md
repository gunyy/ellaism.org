---
permalink: /about/
title: "About"
excerpt: "An Ethereum-like networks with no premine and no contentious hard forks."
modified: 2017-11-21
---

{% include base_path %}

Ellaism это подобная на Ethereum сеть со следующими особенностями:

* Нет премайна.
* Нет постоянных хардфорков. Стабильность является приоритетной.
* Уменьшение награты за блок на 20% через каждые 10 миллионов блоков начиная с награды 5 ELLA за блок.
* Нет бомбы сложности.
* Защита от атаки повторного воспроизведения включена по умолчанию.

Смотрите также [Comparison of Different Ethereum Networks](/comparison/).

## Информация и Сообщество

У Ellaism приветливое и дружное сообщество. Twitter, Discord сервер, форум и другие ресурсы администрируются участниками сообщества.

* [Roadmap](/roadmap/)
* [Principles](/principles/)
* [Get Involved](https://github.com/ellaism/meta)
* [Discord](https://discord.gg/66Pn9jn)
* [Reddit](https://www.reddit.com/r/ellaism/)
* [Community Board](https://board.ellaism.io/)
* [Community Twitter](https://twitter.com/EllaismCoin)
* [Core Twitter](https://twitter.com/EllaismCore)
* IRC: [#ellaism](http://webchat.freenode.net/?channels=ellaism)

## Клиенты

Вы также можете воспользоваться [installation](/install/) или
[mining](/mining/) руководствами для этого раздела.

* [Parity](https://github.com/ellaism/parity-config) (recommended)
* [Geth](https://github.com/ellaism/go-ellaism) (beta)

## Биржи

Вы можете ознакомиться с полным списком бирж [здесь](/exchange/).

* [Cryptopia](https://www.cryptopia.co.nz/Exchange?market=ELLA_BTC)
* [Stocks Exchange](https://stocks.exchange/trade/ELLA/BTC)
* [Bisq](https://bisq.network/)

## Кошельки

* [Web Wallet](https://ellaism.github.io/ellawallet)
* [Chrome Extension Wallet](https://chrome.google.com/webstore/detail/myellawallet/bgfofdgebpphdhddggaggeafenegbjef)

## Аппаратные Кошельки

* [Trezor](https://shop.trezor.io/) with [Web Wallet](https://ellaism.github.io/ellawallet)

## Принять Участие

Поскольку у монеты нет премайна, ее развитием занимается сообщество. Вы можете получить больше информации как присоединиться к сообществу из [ellaism/meta](https://github.com/ellaism/meta) репозитория и [Discord](https://discord.gg/66Pn9jn) сервера. Вы также можете [donate](/donate/) разработчикам Ellaism и членам сообщества чтобы помочь проекту.

## Общая Эмиссия

Ниже представлен анализ эмиссии монет. Тикер монеты "Ella" 
эквивалентен "ETH" для Ethereum. Общее количество монет не привысит 280 миллионов Ella.
К 15.09.2027 около 50% (139 миллионов Ella) будут добыты, а к
20.07.2050 будет добыто около 90% (250 миллионов Ella).

![Total supply](/images/total-supply.png)

## JSON RPC Endpoint

Если вы dapp разработчик, вы можете использовать
"[https://jsonrpc.ellaism.org](https://jsonrpc.ellaism.org)" как JSON RPC
endpoint.

## Техническая Информация

* Время нахождения блока: 10 секунд.
* Генерация монет: 5 Ella за бок с уменьшением на 20% через каждые 10 миллионов блоков.
* Network ID and chain ID is 0x40.
* Большая часть параметров такая же как у Ethereum.

This is an Ethereum network as specified in the [yellow
paper](https://ethereum.github.io/yellowpaper/paper.pdf), with
[Homestead](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2.md),
[EIP150](https://github.com/ethereum/eips/issues/150),
[EIP155](https://github.com/ethereum/eips/issues/155),
[EIP160](https://github.com/ethereum/eips/issues/160) and
[ECIP1017](https://github.com/ethereumproject/ECIPs/blob/master/ECIPs/ECIP-1017.md)
applied from block 0. The era for ECIP1017 is changed to 10 million. Chain id
and network id are both `0x40`. Difficulty bomb is diffused from block 0.

Genesis block contains 0 coins (hence no premine). The initial difficulty in
genesis block is changed to `0x40000000`, its extra data field is
`0x0000000000000000000000000000000000000000000000000000000000000000`, and its
initial nonce is `0x0000000000000040`.
