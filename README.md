<p align="center">
 <img width="100px" src="https://user-images.githubusercontent.com/100832362/157618988-f7191fc8-7259-4879-99eb-cd19f325fab2.png" align="center" alt="GitHub Readme Stats" />



 <h2 align="center">The APIS Readme Stats</h2>
<!--  <p align="center">Get dynamically generated GitHub stats on your readmes!</p> -->
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests Passing" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <br />
    <br />
    <a href="https://www.theapis.xyz">
      <img margin="auto" src="https://www.theapis.xyz/static/img/apis_logo.png"/>
    </a>
  </p>

<h2 align="center">A Decentralized, Scalable Read-Write Solution for Blockchains</h2>
<p align="center">
We propose APIS, a middleware protocol for the functioning of a decentralized
read-write protocol, allowing for the mainstream growth of a fully decentralized finance and
decentralized web architecture. Current data index and querying solutions are either
centrally architected, reliant on a party who at all times is subject to numerous performance
and regulatory risks, or logically decentralized, thus requiring an in-depth knowledge of the
public blockchain protocol layer and obscuring the majority of global developers from
interacting with public blockchain infrastructure. APIS is architecturally decentralized, in
that the providers of the endpointed data can be any actor joins the APIS network, but
logically centralized, in that client-side developers will be able to reference common,
frequented API formatting structures, namely RESTful and GraphQL endpoints, to query
datasets generated by public blockchains.
</p>
# Directory

- Background
  - Background
  - Introduction
   <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157613309-d2b3e2dd-4296-4af0-8d44-956546b76f7f.png"/>
    </p>
<p align="center">Current Decentralized Application Architecture</p>

- Architecture
  - Message Propagation Protocol
  
     <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157614662-651c5168-dd27-4d7d-bbab-a30334dda447.png"/>
    </p>
<p align="center">APIS Network Message Propagation Protocol</p>
 
  - Message Formatting Overview
  
       <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157615544-3cc50864-22e5-4a95-b8b2-128ff967abf4.png"/>
    </p>
<p align="center">APIS RG Comversion Time across internal practical tests</p>


  - APIS Core Contracts
  
   <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157615851-c7a8d0ca-5f20-40ae-8ce9-0e9322ab31e3.png"/>
    </p>
<p align="center">APIS Network Ethereum Layer-One and Layer-Two Architecture</p>


  
  - Governance Contract (GC)
  - Dispute Resolution Contract (DRC) Factory


   <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157616423-aa540c6f-43d1-4fe0-99e2-116f4f8e107f.png"/>
    </p>
<p align="center">DRC Factory Simplified Architecture.</p>

   <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157616678-83bcb126-5cf0-4a2f-850b-1320e3971e5c.png"/>
    </p>
<p align="center">Customized Payment Transaction Structure</p>


  - Optimistic Rollup Contract
  
  <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157616849-7ead65c5-8dc0-4269-a907-d421021ca1f2.png"/>
    </p>
<p align="center">Customized Node State Update Transaction Field.</p>
  

- Applications
  - API Token

  <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157617098-53193e21-7a72-46d0-90e2-53b858767992.png"/>
    </p>
<p align="center">Superfluid API Composition.</p>



  - Token Distribution Community Ownership
- Discussion
- Appendix Analysis of REST versus GraphQL
  - REST History and Analysis
    - Client-Server Architecture
    - Statelessness
    - Cacheability
    - Layered Architecture
    - Uniform Interface
    - Identification of Resources
    - Manipulation of Resources through Representation
    - Self-Descriptive Messages
    - Hypermedia as the Engine of Application State
    - Code on Demand
  - REST APIs in Practice
    - The Endpoint
    - The Method
      - GET
      - POST
      - PUT
      - PATCH
      - DELETE
   - The Headers
   - The Data (or Body)
    - Request
    - Response

  <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157617369-06814815-8ff9-468f-bd46-c4388420b505.png"/>
    </p>
<p align="center">REST API Response.</p>


  - Strengths and Weaknesses of REST
      - Strengths
        - Flexible across languages and frameworks
        - High interpretability
        - Server-side Logic
    - Weaknesses
       - Multiple Round Trip (Latency)
       - Verbose
       - Security with Multiple Endpoints
       - Documentation
       - Updates
 - GraphQL History and Analysis
 - GraphQL as a ‘Fetching Tree’
 - Anatomy of a GraphQL Request
    - Scalars
    - Objects
   
  <p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157617713-572b8964-43fb-46b0-b195-4939c3c5f091.png"/>
    </p>
<p align="center">GraphQL Request.</p>

 - Note on GraphQL Resolvers


<p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157617921-d1abf8ba-6103-43b8-bf92-b9f56bcfc16d.png"/>
    </p>
<p align="center">GraphQL Response</p>


 - Direct Comparison
    - Multiple Round Trip (Latency)
    - Verbose
    - Security with Multiple Endpoints
    - Documentation
 - Weaknesses of GraphQL
    - Schema Design
<p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157618221-5ed7f47b-2c8b-4ccf-b3f7-7a95c8ed2224.png"/>
    </p>
<p align="center"> GraphQL Schema Prefixing.</p>
<p align="center">
      <img margin="auto" src="https://user-images.githubusercontent.com/100832362/157618550-4c99c7cf-894d-44a9-8eb5-e2daacef34b5.png"/>
    </p>
<p align="center"> GraphQL Schema Stitching.</p>
    - Certification and Authorization
    - Routing Design
    - Error Handling
- Bibliography
# GitHub Stats Card

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=merko)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=gruvbox)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=tokyonight)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=onedark)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
