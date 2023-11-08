# PILThermo
Mass Data Collection/Processor/Visualizer for ILThermo

Data Format:
{"Ionic Liquid": 
  {"Data Source" :
    {"citation": "citation of Source",
    "solutes": [["solute 1", "solute 1 molar mass"],["solute 2","solute 2 molar mass"]],
    "solvents": [["solvent 1","solvent 1 molar mass"],["solvent 2","solvent 2 molar mass"]],
    "soluteX": [[solute 1 molality],[solute 2 molality]],
    "solventX": [[solvent 1 molality],[solvent 2 molality]],
    "xd": [x data],
    "xe": [x data error],
    "yd": [y data],
    "ye": [y data error],
    "zd": [z data],
    "ze": [z data error],
    }
  }
}
