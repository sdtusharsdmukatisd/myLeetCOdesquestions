function findMedianSortedArrays(nums1: number[], nums2: number[]): number {
  const array = nums1.concat(nums2).sort((a, b) => a - b);
  let median;
  if (array.length % 2 === 0) {
    median = (array[array.length / 2 - 1] + array[array.length / 2]) / 2;
  } else {
    median = array[Math.floor(array.length / 2)];
  }

  return median;
}

const nums1 = [1, 2];
const nums2 = [3, 4];

console.log(findMedianSortedArrays(nums1, nums2));
