# Golang
## úvod
## Concurrency
## Channels	


# OCI - open container initiative
- definuje standardy pro běh containerů

# Komponenty
- Obraz (image) 
 	- Manifest - definice všech komponent
	- Layout - struktura soubor. systému
	- Vrstvy souborového systému
	- Index manifestů
	- Lze jednoduše sdílet, kopírovat a upravovat
	- Multi OS
- Register 
	- Centrální úložiště pro obrazy (Gitlab, Github)
    - Cloudové = Dockerhub
	- Private = Docker registry
- Kontejnery = Skupina izolovaných procesů, které beží na jednom hostovi
	- Izolace aplikací (sandbox) - procesor, paměť, disk, síť ...
	- Distribuce - obsahuje všechny nutné prostředky ke spuštění
	- Sjednocený způsob pro práci - spuštění, zastavení, výpis

		




# Byzantinské chyby 
- Problém dvou generálů 
	- Nemá řešení kvůli nespolehlivému komunikačnímu kanálu
		- A: zaútočit za úsvitu
		- B: potvrzuji, zaútočit za úsvitu
		- A: potvrzuji, potvrzuji, zaútočit za úsvitu
		- B: potvrzuji, potvrzuji, potvrzuji, zaútočit za úsvitu ...
	- Lze vyřešit snížením nejistoty na přijatelnou mez -> více kurýrů


# ETCD

# GRPC

# Kubernetes
		