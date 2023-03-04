# Obol Bia Testnet

Obol network stack is set up as:
- Execution Client (EC)
- Concensus Client (CC)
- Obol Client
- Validator Client (VC)

The idea is that these can be configured in any arrangement, so I've added a few
examples here. CC and VC should be separate containers, and in many cases the
validator client will need a different config from the consensus/beacon client.
