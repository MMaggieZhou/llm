# llm

Some modules used in large language models like attention 

The inference complexisty per token is O(sequence_l * dmodel^2 + dmodel * sequence_l^2) * Nx + O(sequence_l * dmodel * dff) + O(sequence_l * dmodel * #tokens)
