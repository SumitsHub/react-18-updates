# React 18 Updates
Newly introduced react-18 updates

## Update #01
render method inside index.js

## Update #02
Concurrent rendering - Every component renders twice

## Update #03
useTransition hook - can be used to set priority to state updation
Example- 
const [isPending, startTransition] = useTransition();
startTransition(() => {
    // Low priority code goes here...
});
isPending shows whether low priorit task is complete or not