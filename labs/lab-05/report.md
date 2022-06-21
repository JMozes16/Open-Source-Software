
Steps 1 and 2:
![image](https://user-images.githubusercontent.com/85561037/174329222-af96b29f-5054-4f1e-ad34-443a1a3001b4.png)
![image](https://user-images.githubusercontent.com/85561037/174335738-14f33c28-10f4-4613-9a36-df2074c5dc45.png)
![image](https://user-images.githubusercontent.com/85561037/174336660-4bd6c2bc-0dbd-43fa-8a0e-3ea098c92036.png)
![image](https://user-images.githubusercontent.com/85561037/174336746-5eddb308-35e9-4097-b15a-af96324b78f9.png)

Step3:
![image](https://user-images.githubusercontent.com/85561037/174337873-44c519e0-1426-4ac5-b787-a10cf4b05578.png)
![image](https://user-images.githubusercontent.com/85561037/174337956-c8fe9860-a2d7-4827-91fc-f90fb1d0f837.png)
![image](https://user-images.githubusercontent.com/85561037/174338000-4556f5c3-67b1-416c-93ca-bcc0316c3a64.png)

Step 4:
ctest -VV:
![image](https://user-images.githubusercontent.com/85561037/174668175-a4a846aa-f5f8-48fc-8538-adce4bcfdb65.png)
MathFunctions/CMakeLists:
![image](https://user-images.githubusercontent.com/85561037/174668282-edcc1f97-8ba9-46a8-b682-85686ee37d21.png)
CMakelists:
![image](https://user-images.githubusercontent.com/85561037/174668354-b9197bae-7f8a-4495-8d12-c33b13130af5.png)
![image](https://user-images.githubusercontent.com/85561037/174668419-31f07a6a-22d6-46fa-b35b-10e27198409b.png)
![image](https://user-images.githubusercontent.com/85561037/174668448-eecbca8a-dd45-4d72-80eb-bebda5fa2c82.png)

Step 5:
Output:
![image](https://user-images.githubusercontent.com/85561037/174671551-ad7855ed-937b-40d7-97d7-334819ede54d.png)
MathFunctions/CMakeLists:
![image](https://user-images.githubusercontent.com/85561037/174671673-c559c872-d1f9-42e3-acec-4aba7a0a242d.png)
CMakeLists:
![image](https://user-images.githubusercontent.com/85561037/174671734-6e9c1a8b-3e30-4a93-98ce-071714649beb.png)

## Part 2:

Output:
![image](https://user-images.githubusercontent.com/85561037/174698399-661d5bd3-67bb-4526-8e30-0a697faf78f9.png)

Makefile:
![image](https://user-images.githubusercontent.com/85561037/174699006-01c11ea9-65b5-4597-863f-a272c2c7e037.png)

CMake file:
![image](https://user-images.githubusercontent.com/85561037/174700180-b8752dde-73d7-4d7e-a9a8-1449ae71d6ee.png)

Generated Makefile submitted seperately.

Size of executables:
![image](https://user-images.githubusercontent.com/85561037/174700578-c7a0943f-6ef0-409b-9d5d-4bbfabb88a03.png)
They have similar sizes, but the static_block is 16856, while the dynamic block is 16696 bytes. So the dynamic block (shared lib) is a little smaller than the static one.
