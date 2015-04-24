# NOTE #

This repository represents an early Alpha test of Tonika from 2010. The repository is now
obsolete and remains here for reference purposes. If you want to compile this code you
would either (a) have to use a version of the Go Language dated around the same time
of the repository's last commit, or (b) update the code to factor in language changes in
Go Language.

Tonika is still in active development. From now on, all Tonika-related projects
are hosted on [my GitHub account](http://github.com/petar). For up-to-date
information on the development effort, please refer to the
[Tonika Blog](http://blog.5ttt.org).

# Organic security #

A (digital) social network, which (by design) restricts direct communication to pairs of users who are friends, possesses many of the security properties (privacy, anonymity, deniability, resilience to denial-of-service attacks, etc.) that human sociaties implement organically in daily life. This is the only known decentralized network design that allows open membership while being robust against a long list of distributed network attacks. We call a digital system with such design an organic network and the security that it attains for its users — organic security. Organic networks are extremely desirable in the current Internet climate, however they are hard to realize because they lack long-distance calling. Tonika resolves just this issue.

# Long-distance calling #

At its core, Tonika is a routing algorithm for organic networks that implements long-distance calling: establishing indirect communication between non-friend users. Tonika is robust (low-latency, high-throuhgput connectivity is achieved in the presence of significant link failures), incentive-friendly (nodes work on behalf of others as much as other work for them), efficient (the effective global throughput is close to optimal for the network's bandwidth and topology constraints) and real-time concurrent (all of the above are achieved in a low-latency, real-time manner in the presence of millions of communicating parties).

# Some application areas #

Internet (bandwidth) neutrality. Freedom, no-censoring and no-bias of speech on the Internet. Scalable open Internet access in all countries. User ownership of data and history in social applications. Cooperative cloud computing without administration. Etc.