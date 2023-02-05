# Timeouts
 
function repeatingFunc() {
 console.log("It's been 5 seconds. Execute the function again.");
 setTimeout(repeatingFunc, 5000);
}
setTimeout(repeatingFunc, 5000);
