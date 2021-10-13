# DamBOX

DamBOX is a software developed in C++ that intermittently releases the packet on the interface, like a dam : using netfilter, incoming packets are intercepted and blocked until released at the interface goodput. The user specifies the duration and frequency of the blocking and releasing function. DamBOX can be used to emulate beam hopping in satellite telecommunication system.
