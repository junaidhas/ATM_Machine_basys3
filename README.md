# ATM Machine Project in Verilog Implemented on Basys 3 Board

## Overview
This project implements an ATM (Automated Teller Machine) system using Verilog HDL (Hardware Description Language) on a Basys 3 FPGA development board. The ATM system simulates basic banking functionalities such as account balance inquiry, cash withdrawal, and deposit, with additional features for enhanced functionality and user feedback.

## Features
- **User Interface**: The system provides a user-friendly interface using a combination of input buttons and display modules on the Basys 3 board.
- **Balance Inquiry**: Users can check their account balance.
- **Cash Withdrawal**: Users can withdraw a specified amount of cash from their account.
- **Deposit**: Users can deposit funds into their accounts, with a maximum deposit limit of $255, as implemented using an 8-bit counter. LED indicators provide feedback when the maximum deposit limit is reached.
- **Dollar Bill Selection**: Six switches are utilized to select different dollar bill denominations ($1, $5, $10, $20, $50, $100), enhancing flexibility for transaction amounts.
- **LED Feedback**: LED indicators provide visual feedback to the user:
  - `LED[0]`: Lights up when the maximum deposit limit is reached.
  - `LED[1]`: Indicates when more than one switch is selected simultaneously.
  - `LED[2]`: Lights up when there are insufficient funds to complete a withdrawal request.
    
## Demo

https://github.com/junaidhas/ATM_Machine_basys3/assets/97498014/3a4c525b-205a-4793-bfc2-4c3aee83c72d



## Implementation Details
- **Verilog HDL**: The project is developed using Verilog HDL to describe the hardware behavior and logic of the ATM system.
- **Basys 3 Board**: The Verilog code is synthesized and implemented on the Basys 3 FPGA development board, utilizing its hardware components for interfacing and transaction management.
- **Simulation**: Simulation tests are conducted to verify the correctness and functionality of the ATM system, ensuring accurate behavior in different scenarios.
- **Documentation**: Detailed documentation is provided to explain the design, implementation, and usage of the ATM system, including instructions for setup and interaction.

## How to Use
1. **Setup**: Connect the Basys 3 board to a power source and a display monitor.
2. **Compile**: Synthesize the Verilog code using a compatible FPGA synthesis tool.
3. **Upload**: Upload the synthesized design onto the Basys 3 board.
4. **Interaction**: Follow the on-screen instructions to interact with the ATM system using the provided input buttons, switches, and LED indicators.

## Contributions
Contributions to improve the functionality, performance, or documentation of the project are welcome. Please fork the repository, make your changes, and submit a pull request for review.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Special thanks to [Basys 3](https://reference.digilentinc.com/reference/programmable-logic/basys-3/start) for providing the hardware platform for this project.
