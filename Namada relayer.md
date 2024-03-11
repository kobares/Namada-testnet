IBC Namada - Osmosis relayed by **KOBARES**

|  | Namada | Osmosis |
| -------- | ------ | ------- |
| Chain_id         |   shielded-expedition.88f17d1d14     |   osmo-test-5      |
| Channel_id    |    channel-752    |    channel-6223     |
| Client_id   | 07-tendermint-2560   | 07-tendermint-2573    |

*IBC transaction from Namada to Osmosis:*
https://www.mintscan.io/osmosis-testnet/tx/A238D20D792B0BBF70DB076EACAABE400CDC64AE7CD8D6476CB8EBC401EE0298?height=5942925

*IBC transaction from Osmosis to Namada:*
https://www.mintscan.io/osmosis-testnet/tx/2A6EB355E3248885B495954CFCD0C3BDDC9AE26278CBF4E5B5D3559F7895D10F?height=5942885

*Hermes log:*

    SUCCESS Channel {
        ordering: Unordered,
        a_side: ChannelSide {
            chain: BaseChainHandle {
                chain_id: ChainId {
                    id: "shielded-expedition.88f17d1d14",
                    version: 0,
                },
                runtime_sender: Sender { .. },
            },
            client_id: ClientId(
                "07-tendermint-2560",
            ),
            connection_id: ConnectionId(
                "connection-1231",
            ),
            port_id: PortId(
                "transfer",
            ),
            channel_id: Some(
                ChannelId(
                    "channel-752",
                ),
            ),
            version: None,
        },
        b_side: ChannelSide {
            chain: BaseChainHandle {
                chain_id: ChainId {
                    id: "osmo-test-5",
                    version: 5,
                },
                runtime_sender: Sender { .. },
            },
            client_id: ClientId(
                "07-tendermint-2792",
            ),
            connection_id: ConnectionId(
                "connection-2537",
            ),
            port_id: PortId(
                "transfer",
            ),
            channel_id: Some(
                ChannelId(
                    "channel-6223",
                ),
            ),
            version: None,
        },
        connection_delay: 0ns,
    }
