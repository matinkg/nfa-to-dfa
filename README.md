# NFA to DFA Converter

This is a web-based tool for converting Nondeterministic Finite Automata (NFA) to Deterministic Finite Automata (DFA). The converter provides both a visual representation and a JSON format of the automata.

## Demo

A demo of the NFA to DFA Converter is available at [Demo](https://matinkg.github.io/nfa-to-dfa/).

## Getting Started

To use the NFA to DFA Converter, simply open the `index.html` file in a web browser or deploy it on a web server. The tool allows you to interactively build and convert automata.

### Prerequisites

Make sure you have a modern web browser that supports HTML5 and JavaScript.

## Features

- **Interactive NFA Building:**
  - Add states, transitions, accept states, and set the start state.
  - Remove states, transitions, and accept states.
  - Clear the NFA.

- **Export and Import:**
  - Export the current NFA configuration to a JSON file.
  - Import a previously exported NFA configuration.

- **Visual Representation:**
  - See a visual representation of the NFA and DFA.
  - Use SVG graphics to display states, transitions, and accept states.

- **Conversion to DFA:**
  - Convert the NFA to a DFA with a single button click.
  - View the DFA in both JSON and visual representation formats.

- **Dtrans Table:**
  - Display the transition table (Dtrans Table) during the conversion process.

## Instructions/Help

1. Add states, transitions, and set the start state in the NFA section.
2. Explore additional features such as clearing, exporting, and importing.
3. Use "epsilon" as a symbol for ε transitions.
4. Convert NFA to DFA using the "Convert NFA to DFA" button.
5. Review the DFA in the visual representation and JSON format.
6. Experiment with different automata configurations.

## Known issues

- <del>The converter will crash if there are loop epsilon transitions in the NFA.</del>

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit PR.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Bootstrap](https://getbootstrap.com/) - Front-end framework.
- [dagre-d3](https://github.com/dagrejs/dagre-d3) - Graph layout library for visualizing automata.
- [jQuery](https://jquery.com/) - JavaScript library for DOM manipulation.
- [d3.js](https://d3js.org/) - JavaScript library for creating dynamic, interactive data visualizations.
