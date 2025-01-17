# React useEffect setInterval memory leak
This example demonstrates a common mistake when using setInterval within a React component's useEffect hook.  Forgetting to include a cleanup function in the useEffect hook leads to memory leaks, especially when the component unmounts but the interval continues to run. This results in unintended behavior and potential performance issues. The solution shows how to properly implement a cleanup function to address the memory leak issue.