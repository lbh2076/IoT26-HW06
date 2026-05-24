// Target license plate
var targetPlate = "sam123";

var results = msg.payload.results;
if (results && results.length > 0) {
   var plate = results[0].plate.toUpperCase();
   if (plate === targetPlate.toUpperCase()) {
       msg.payload = 1; // Authorized: turn LED on
   } else {
       msg.payload = 0; // Unauthorized: turn LED off
   }
} else {
   msg.payload = 0; // No plate detected
}
return msg;
