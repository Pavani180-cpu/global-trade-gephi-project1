# global-trade-gephi-project1
Network visualization using Gephi to explore trade patterns

#  Network Visualization and Analysis of International Trade Flows

This project explores **global trade connections** between countries using **network visualization in Gephi**.  
Countries are represented as **nodes**, and their trade relationships are **edges** weighted by trade volume.

---

##  Objective
To map and analyze international trade flows and uncover:
- Economic connections between countries  
- Key trade hubs and influencers  
- Regional trade communities and dependencies  

---

##  Data & Tools
- **Trade Data**: Derived from WTO datasets (import/export values)
- **Country Coordinates**: Obtained from open-source API datasets
- **Tool Used**: [Gephi](https://gephi.org/) for visualization and analysis

---

##  Methodology
1. **Network Construction**
   - Nodes represent countries
   - Directed, weighted edges show trade flow (A → B means A exports to B)
   - Edge weights are trade volumes (USD)

2. **Centrality Analysis**
   - **Degree Centrality** → Identifies countries with the most trade partners  
   - **Betweenness Centrality** → Highlights countries acting as trade bridges  
   - **Eigenvector Centrality** → Measures influence within the global trade network  

3. **Clustering & Modularity**
   - Detected **6 major communities** of countries
   - Modularity score: **0.194** (moderate clustering)
   - Groups reflect real-world trade blocs (e.g., EU, ASEAN)

4. **Homophily Observation**
   - Countries with similar trade behaviors cluster together
   - Example: USA–Canada–Mexico and EU nations show dense internal connectivity

5. **Strongly Connected Components**
   - 69.57% of countries belong to one large connected trade group
   - Indicates global interdependence

6. **Comparison with Random Network**
   - Trade network follows **power-law distribution**
   - Real-world trade shows non-random, structured connectivity

---

## 🌐 Results & Insights
- **Global Connectivity** → 70% of countries are tightly linked  
- **Key Players** → USA and China dominate global trade flow  
- **Regional Alliances** → EU and ASEAN show strong intra-group trade  
- **Influencers vs Connectors** → Korea (influencer), South Africa (connector)  
- **Non-Random Patterns** → Trade depends on geography and economy  

---

##  Tools Used
- **Gephi** – For visualization and centrality analysis  
- **Excel / CSV** – Data preparation and cleaning  


---

##  Author
**Lakshmi Pavani Raghavaraju**  
Master’s in Data Science and Business Analytics, UNC Charlotte  
Charlotte, NC | r.lakshmipavani@gmail.com  

