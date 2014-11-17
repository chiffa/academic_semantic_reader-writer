Requirements:
 - Must be able to write pdf and xml/markdown/enriched text formats
 - Must be able to read xml, markdown and enriched text formats
 - Must be able to atocomplete from imported namespaces
 - Must be able to represent logic and supporting natural text as a graph
 - Must be able to import ontologies and match terms agaisnt them
  - BioPax for Reactome
  - GO
  - Terms tagged as unfoldable (inner definition / abbreviation / bibliography / supplementary data / figure)
    - fallback behavior of verification of googlability / wikipediability of terms that are not in the main dictionary
- Must be able to match inner definitions (abbreviations, model names) and support linking to definitions
  - The idea is to treat them as binding a function to a variable in programming languages and re-using the variable elsewhere
  - Attach rationale to the inner/outer term declaration 
  - Warn if the terms are used in text prior to their rationale declaration.

Suggestions: 
 - Use the IntelliJ framework
 - OR build as an extension to Emacs/vim based on python
 - enable flushing down to a normalized semantic wiki repositry (Python) with proper links and multi-nodes represented by papers.
