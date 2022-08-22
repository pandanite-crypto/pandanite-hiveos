# bamboo-hiveos

# Setup Guide

## Create Wallet

In your hiveos dashboard create a new wallet.

Ticker: BMB

Address: your address

Name: choose a name for your wallet

Source: leave blank

## Edit existing Flight Sheet or create new one

Coin: BMB

Wallet: select the wallet you created earlier

Pool: 'Configure in miner'

Miner: select 'custom' as your miner and click on 'Setup Miner Config'

## Miner Config

Name: dcrptminer

Installation URL: choose a realease from [here](https://github.com/f10crypto/bamboo-hiveos/releases/latest), find dcrptdminer.tar.gz, right-click and copy link address

Hash algorithm: leave blank

Wallet and worker template: %WAL%.%WORKER_NAME%

Pool URL: your desired pool URL (shifu://185.215.180.7:5555 or stratum+tcp://bmb.ffmpool.com:4444)

Pass: leave blank

Extra config arguments: choose desired arguments ('--pufferfish2bmb:threads 4' to choose amount of threads(4))

## Issues
reported CPU temp & fan speed are zero
hashrate is displayed in kH/s but its actually only H/s
