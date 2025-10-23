/* This problem wants us to find the longest common prefix from an array of strings.
   Here we can start with comparing first two elements and finding the common prefix and then compare this new prefix with next element.
  Keep repeating this until we reach the end of the array or our prefix return empty string.
*/
public String longestCommonPrefix(String[] strs) {
        String res = strs[0];
        for(int i=1; i<strs.length; i++){
            res = commonPrefix(res, strs[i]);
            if(res.isEmpty()){
                return res;
            }
        }
        return res;
    }
    public String commonPrefix(String a, String b){
        int i=0; 
        int j=0;
        StringBuilder sb = new StringBuilder();

        while(i<a.length() && j<b.length()){
            if(a.charAt(i)!=b.charAt(j)){
                return sb.toString();
            }
            sb.append(a.charAt(i));
            i++;
            j++;
        }

        return sb.toString();
    }

  
