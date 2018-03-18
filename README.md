# Creative Logic Architecture

The Creative Logic Architecture is an intelligent agent architecture that learns to generate high-level patterns in order to reason and make judgments about the world and its own behavior. The agent creates structures of logic using an internal language resembling computer code, and then executes the code to manipulate the information stored in memory. Statements written in this language are called scripts, and are generated through a goal-oriented selection process, by applying knowledge of different operations and there effects on the output to formulate a structure with the desired result.

The ability to guide mental function in this way grants the agent behavioral control that extends beyond reactionary decision-making. Strategies that rely on pure reinforcement to train an agent tend to link sensory states more or less directly to behavioral outputs, creating a decision process that fails to take long-term, difficult, or unrewarding goals into account. The role of scripts in the decision making process is to intervene in this state-to-action process with a rational system of logic that’s less swayed by immediate reward. Through this method, agents are given an internal control mechanism that favors a logical reflective process over the more primitive emotional functions.

Goals are linked to specific patterns that make up sensory and cognitive states, allowing the agent to conceptualize what changes it has to make and reason about the best ways of doing so. Scripts are then selected based on the current and goal state, as well as the knowledge about possible trajectories and the scripts that yield the correct behavior to move along those trajectories. The desired trajectory is conceptualized as a pattern, which describes a sequence of events, actions, and expectations as an outline for the agents decision making process. This includes potential events that indicate progress, which create a sort of emulation of reinforcement.

Agents consist of three long-term memory modules, each with different elements that are used to create objects. The first contains a set of templates that outline the various requirements and attributes of specific objects. The second contains a set of operations along with knowledge on how they work when combined into logical hierarchies and translated into scripts. The last module contains a set of variables that are acted upon and manipulated by the operations when called by a script.

There are two other modules, namely short-term and working memory. They are distinct in that the short-term contains information about patterns detected in the input space, as well as the current plans and goals at any given time. Working memory deals with partial constructions of objects, which takes the information in short-term memory and uses it to fill in various elements of the objects being constructed.

Objects are high-level descriptions of patterns. An object is network-like structure with a small number of nodes that are highly interrelated. each node represents a bit of data and each link an operation. The data stored in a node is passed to each connected link, producing a set of outputs that describes its relationship with other data stored in the object. The total set of outputs produced by the operations are used to reason about the implications of the object, particularly how current goals and plans change with respect to that object. The results of objects therefore influence behavior by conveying assumptions, which are functions of the current sensory and cognitive states.

Templates are selected from a template vector, which is a subset of all possible templates called the template space. When a selected template is made into an object, it activates connections to other templates. Those templates are then moved to the template vector given that their net activation reaches a threshold. When any two templates become active within a short timespan of one another, the strength of their connection increases and therefore causes any future activations to be stronger. Conversely, when any two templates rarely become active near one another, their connection is weakened and eventually decays to the point of disconnection (which can potentially be reversed).

The process of searching a subset based on previous activity of templates in a network allows the agent to quickly find a valid template to form an object that models the current state, by avoiding an exhaustive search of the template space. Because templates can only form an object if the elements assigned by the working memory meet the constraints of that template, then only successful selections result in activation. Thus the network adapts to accurate implications of future success, allowing potentially useful templates to inferred and made readily available to the working memory.

To generate an object, the agent must match a set of variables (input features) to the elements of some template, such that the net output of the constraint operations meet an acceptable value. Given a set of input features, the templates currently stored in the template vector are assigned combinations of features and checked for constraint violations. Each template can then be judged according to the rate at which they are successfully assigned, providing a fitness that determines whether a template should remain as a valid candidate or whether it should be disqualified from the matching process.

Qualification is competitive in the sense that each fitness rating has an inhibitory effect on the other, meaning the most successful template tends to remain qualified as its inhibitory effect is stronger than all other candidates. The matching process continues until a successful candidate is found, otherwise the best candidate is selected after a certain time despite not satisfying the constraints. If this occurs, then a local search is conducted in the template space where the similar templates that share the valid elements of the best template are transferred to the template vector, where the matching process occurs once more.

This continues until a successful template is found or until the amount of time looking for a match extends beyond some acceptable range, which is determined by the perceived importance of finding a match based on the current goals of the agent. Given an adequately important goal, the agent constructs a new template that encompasses the a description of the structural aspects of the input, which it then stores in the input space as well as the input vector, allowing it to form connections with the unsuccessful candidates so that a future instance of the same search would return the newly created template and result in a successful match.
