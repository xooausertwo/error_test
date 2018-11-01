## Error cases to test for

1. Assert errors are passed from app to user
2. Make app sleep with a function in chaincode. Sleeptime should be managed via the argument. Call invoke while the app is sleeping
3. Crash a smart contract by creating a segmentation fault in main()
4. Missing return statement (Handled by go compiler)
5. Return error from Init() instead of success
6. Setting the key for PutState with invalid param and unavailable param
7. Folder containing chaincode to have spaces ex: Smart Contract
8. Creating a infinite loop
9. Divide by zero error when the param is zero
10. Deploying an empty chaincode
11. Missing yaml and malinformed yaml
