# Intelligence cycle

The intelligence cycle is an idealized model of how intelligence is processed in civilian and military intelligence agencies, and law enforcement organizations. It is a closed path consisting of repeating nodes, which (if followed) will result in finished intelligence. The stages of the intelligence cycle include the issuance of requirements by decision makers, collection, processing, analysis, and publication (e.g., dissemination) of intelligence [[4]](../references.md#4).

## Concepts

To explain the phases of this cycle, we must first define the following terms:

- **Data**: Collection of discrete values that convey information, describing quantity, quality, facts, statistics, other basic units of meaning, or simply sequences of symbols that can be interpreted later. A datum is an individual value within a data set. Data are usually organized into structures, such as tables, which provide additional context and meaning, and in turn can be used as data within larger structures.

- **Information**: Term used to refer to a set of processed data that, when combined, allow answering a simple question. Information is the output of processed data that contains meaning and context. Therefore, information can be considered as the knowledge generated when a set of data providing different facts about an event are combined or interconnected to provide an overview of that event or to answer a question.

- **Intelligence**: It is the product resulting from the collection, processing, and analysis of data and information about threats, which provides contextualized, timely, and actionable knowledge to identify, anticipate, and mitigate risks in cyberspace.

## Phases

The intelligence cycle is composed of these phases:

1. **Direction:**  
  Intelligence requirements are determined by a decision maker to meet their objectives.

2. **Collection:**  
  In response to requirements, an intelligence staff develops an intelligence collection plan applying available sources and methods and seeking intelligence from other agencies. Collection includes inputs from several intelligence gathering disciplines, such as HUMINT (human intelligence), IMINT (imagery intelligence), ELINT (electronic intelligence), SIGINT (signals intelligence), OSINT (open source, or publicly available intelligence), data from the Dark Web, etc.

3. **Processing and exploitation:**  
  Once the collection plan is executed and the data arrives, it is processed for exploitation. This involves translation of raw intelligence materials from a foreign language, evaluation of relevance and reliability (e.g., with the Admiralty Code [[3]](../references.md#3)), and collation of the raw data in preparation for exploitation.

4. **Analysis:**  
  Analysis establishes the significance and implications of processed intelligence. It integrates information by combining disparate pieces of data to identify collateral information and patterns, then interprets the significance of any newly developed knowledge.

5. **Dissemination:**  
  Finished intelligence products take many forms depending on the needs of the decision maker and reporting requirements.

The intelligence cycle is a closed loop; feedback is received from the decision maker and revised requirements issued.

<div style="width: 100%; text-align: center;">
```mermaid
graph TD
    %% Nodos (Uso de comillas para evitar errores de sintaxis)
    Phase1["<b>1. Direction</b>"]
    Phase2["<b>2. Collection</b>"]
    Phase3["<b>3. Processing and exploitation</b>"]
    Phase4["<b>4. Analysis</b>"]
    Phase5["<b>5. Dissemination</b>"]

    %% Conexiones
    Phase1 -->|Define needs| Phase2
    Phase2 -->|Raw data| Phase3
    Phase3 -->|Processed information| Phase4
    Phase4 -->|Intelligence| Phase5
    
    %% Bucle de Retroalimentación
    Phase5 -.->|Feedback and <br/>revised requirements| Phase1
```
</div>