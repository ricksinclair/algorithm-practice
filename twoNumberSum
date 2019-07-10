function twoNumberSum(array, targetSum) {
	
	let sortedArray = array.sort((a, b) => a - b)
	
	let left = 0;
	let right = sortedArray.length - 1 ;
	while(left < right){
		let currentSum = sortedArray[left] + sortedArray[right]
		if ( currentSum === targetSum){
			return [sortedArray[left], sortedArray[right]]
		} else if(currentSum < targetSum){
			left += 1;
		}else if (currentSum> targetSum){
			right -= 1;
		}
		
			

}
return []
}
