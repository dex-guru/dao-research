# Mathematics behind DAO decentralization

Two key properties that set a DAO apart from a traditional corporation are emphasis on decentralization and autonomous properties. Put mathematically, autonomous can be replaced with the word ‘independent or invariant’.

**Theorem:** Consider a n node planar graph. Then a graph is maximally decentralized if and only if the graph is [complete](https://en.wikipedia.org/wiki/Complete_graph).

**Proof by pictures:**

Here is an example of what a fully connected bidirectional graph looks like (top pair of images). The key property is that each node is connected to every other node.

[https://lh4.googleusercontent.com/RfWIfdUbkAtLym3SgtL39KdB9x-2ViaRIQ-KrBSWAuYccC155IwQ38ng-PpfUPFaL3sF52eH1jIQYODT_lgl4GAQtCBlBkFmcY68xZx_Q4rwqOZIzQG92gty6YOdzE5tHyTFh36T](https://lh4.googleusercontent.com/RfWIfdUbkAtLym3SgtL39KdB9x-2ViaRIQ-KrBSWAuYccC155IwQ38ng-PpfUPFaL3sF52eH1jIQYODT_lgl4GAQtCBlBkFmcY68xZx_Q4rwqOZIzQG92gty6YOdzE5tHyTFh36T)

[https://lh6.googleusercontent.com/VeCLr-5q-frPlELspSPBCG92Z56mhmhqZ6SUPmtZUXriEW8r_EvOUBNoKAKgCVZBu_hxX6dcS4sXT4EH_Ip0bcj4xDg_EW8b9q3gDLXKz8BdbLcPN0J8yDkPrRFNYupMLXgl__r5](https://lh6.googleusercontent.com/VeCLr-5q-frPlELspSPBCG92Z56mhmhqZ6SUPmtZUXriEW8r_EvOUBNoKAKgCVZBu_hxX6dcS4sXT4EH_Ip0bcj4xDg_EW8b9q3gDLXKz8BdbLcPN0J8yDkPrRFNYupMLXgl__r5)

If we take away node 4 from the right graph, we are left with a triangle, which is still fully connected. If we add node 5, or up to n total nodes, then the graph will still be fully connected. Thus there is no friction when adding/removing nodes from a fully connected graph. This implies that the number of nodes is independent of the level of autonomy of the graph. This immediately implies that no node relies on another node.

Consider the opposite of a complete graph shown in the pair of graphs in the second picture. These represent a maximally centralized structure because if node 2 from either graph is removed, the graph will no longer be connected because the central node was removed, thus ending the proof (we just take the contrapositives of the two examples to get equivalence to finish the proof but I’ll leave that as a thought exercise :) ).

Let’s consider two examples I’ve taken from discussion in the discord of possible DAO structures where each ‘team’ represents an individual node.

[https://lh3.googleusercontent.com/jW4RoiH2L70SBq0GOjUTIK2gbok1ForpPeYJEAAtBkzp146vMHrhpFEdqc2_hVO3ypB0QwLt2YKjFOC-fXKaRRRx6t9EJ8BE4PUUTOrSZhxSVd3SDo5Mozv7TFGnkdx0Aub8uV_Z](https://lh3.googleusercontent.com/jW4RoiH2L70SBq0GOjUTIK2gbok1ForpPeYJEAAtBkzp146vMHrhpFEdqc2_hVO3ypB0QwLt2YKjFOC-fXKaRRRx6t9EJ8BE4PUUTOrSZhxSVd3SDo5Mozv7TFGnkdx0Aub8uV_Z)

Since the theorem above ‘proves’ that a complete graph is maximally decentralized and autonomous, we should aim towards a DAO structure that can be represented as a complete graph. For example let’s take a look at the treasury nodes. For simplicity's sake I will  only refer to the complete graph to the left in this example.

The treasury node is connected to all the other nodes (by definition of the graph being complete) - product, engineering, bus dev, pr/marketing, community, and people, which is important because treasury decisions will impact each of the other roles. However if the treasury node is removed, being a complete graph implies that the other nodes should not be affected by the removal of the treasury node. Each other node, which by definition is maximally decentralized and thus independent, would have to pivot and absorb/pick up functions of the treasury in order to regain the maximally decentralized/independent property.

The solution would be to delegate functions of the treasury node as responsibilities for other nodes so that in the event the treasury node is removed, the other nodes will maintain decentralization/autonomy. Similarly the creation of a treasury node and the assigning of roles and responsibilities within the treasury team should be designed in a way that adds value to every other node, but when taken away will only have a minimal impact on operational efficiency.

**Remark 2 - roles are hard to define in a DAO, but this is a feature not a bug.**

Viewing a DAO structure through the eyes of a complete graph explains the interleaving effect and why the roles of DAO members appear so blurry, it’s because they are and the blurriness is actually a feature, not a bug of a successful DAO structure. There is blurriness associated with each role because there are such a large number of connections within each complete graph. In fact, for a complete graph which has n nodes, each node will be connected to every other node by n-1 edges. Thus there are (n-1)^n possible edges between nodes to consider and as n gets larger, the complexity grows exponentially.

**Remark 3 - Team roles should be designed based on desired level of decentralization/centralization**

Would be my recommendation to first understand how many nodes we should have and what those nodes should be responsible for. Note that we don’t necessarily need a complete graph, but the closer to a complete graph we get to, the more we will maximize decentralization. A DAO is finding a balance between centralization and decentralization so it doesn't need to be a complete graph to function well.

### Links

[The mathematics behind a maximally decentralized autonomous DAO structure - Google Docs](https://docs.google.com/document/d/1_rPODDWQhZu6oAoQQiy_3oQngOVhu8XLuqeLFgk1Yzg/edit)