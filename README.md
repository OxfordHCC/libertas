# Libertas

- - - - - -

![Overview](libertas.png)

Libertas is a framework for efficiently performing privacy-preserving computation on decentralized contexts such as personal data stores.
It combines (Secure) Multi-Party Computation (MPC) with Solid (Social Linked Data), addressing the key challenges of decentralization. It also demonstrates how Differential Privacy can be employed in this context, leading to both input and output privacy.

Preprint available at https://arxiv.org/abs/2309.16365

[This repo](https://github.com/OxfordHCC/libertas) is the indexer repository for our prototype implementation. The implementation contains several parts, in different repositories:

- [MPC App](https://github.com/OxfordHCC/solid-mpc-app): This repository contains the source code for the example MPC App for performing MPC in Libertas
- [Agent services](https://github.com/OxfordHCC/solid-mpc): This repository contains the source code for agent services (for encryption agent and computation agent)
- [Specification](./spec/index.html): The specification (using ReSpec) of Libertas, containing details of the protocol and interactions

Please refer to the README in each repository for further details.


## Citing this work
```
@misc{zhao2023libertas,
      title={Libertas: Privacy-Preserving Computation for Decentralised Personal Data Stores}, 
      author={Rui Zhao and Naman Goel and Nitin Agrawal and Jun Zhao and Jake Stein and Ruben Verborgh and Reuben Binns and Tim Berners-Lee and Nigel Shadbolt},
      year={2023},
      eprint={2309.16365}
}
```

