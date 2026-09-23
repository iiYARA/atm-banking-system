# ATM Banking System

**Java · Swing / JavaFX · MySQL**

A banking application with a customer ATM interface and an admin dashboard. The source includes deposits, withdrawals, balance enquiries, PIN changes, statements, and account-management screens.

## Explore the code

| Area | Files |
| --- | --- |
| Customer access | [Login](src/bank/Login.java), [registration](src/bank/SignUpOne.java) |
| Transactions | [Deposit](src/bank/Deposit.java), [Withdraw](src/bank/Withdraw.java), [Balance enquiry](src/bank/BalanceEnquiry.java) |
| Account tools | [PIN change](src/bank/PinChange.java), [Mini statement](src/bank/MiniStatement.java) |
| Administration | [Dashboard](src/bank/Dashboard.java), [Account list](src/bank/ListAccountsController.java) |
| Database connection | [Conn.java](src/bank/Conn.java) |

## Setup status

This is a source-code portfolio repository. It currently requires environment and project configuration work before it can be treated as a reproducible local demo.

The checked-in NetBeans configuration targets **JDK 17** and a **JavaFX 17** library. It also references machine-specific library locations. Several JARs are stored in `src/bank/`, but those paths do not match all references in the project configuration.

### Before running

1. Clone this repository:
   `git clone https://github.com/iiYARA/atm-banking-system.git`
2. Open it in NetBeans and configure JDK 17, JavaFX, and the required libraries.
3. Review package/source paths and repair the library references in [nbproject/project.properties](nbproject/project.properties).
4. Configure a local MySQL database using [Conn.java](src/bank/Conn.java). A database schema export is not included in this repository.
5. Review image/resource paths before launching the application.

## Attribution

The previous README referenced [Asirwad/ATM-management-system](https://github.com/Asirwad/ATM-management-system) as the source project. That reference is preserved here for attribution. This repository should not be presented as an entirely original implementation; a detailed list of adaptations is not currently documented.

## Contact

[Yara Mohammad](https://github.com/iiYARA) · [Email](mailto:YaraMohammadSA@gmail.com)

