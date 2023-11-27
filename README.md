# Process-ILThermo (PILThermo)
PILThermo is an modular, automated mass data collection/processor/visualizer for the Ionic Liquids Database(https://ilthermo.boulder.nist.gov/)

## Description:
PILThermo has been developed to enable data collection and visualization of the Ionic Liquids Database. PILThermo is able to compile datasets within the Ionic Liquids Database by properties(e.g. Viscosity) and generate a downloadable .json file in the format listed below. PILThermo automatically standardizes all measurements of concentration into molality, releasing all references where it is unable to do so.

## Data Format:
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
