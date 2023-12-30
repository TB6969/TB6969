	/**
 * Generates a Vbucks code.
 *
 * @returns {string} A randomly generated Vbucks code.
 */
function generateVbucksCode() {
    // Generate a random 12-digit number
    const code = Math.floor(Math.random() * 1000000000000).toString().padStart(12, '0');
    return code;
}
 
// Usage Example for generateVbucksCode
 
const vbucksCode = generateVbucksCode();
console.log(`Generated Vbucks code: ${vbucksCode}`);
