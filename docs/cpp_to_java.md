# Documentation

unordered_map<int,int> m; ----------->            Map<Integer, Integer> m = new HashMap<>();

m[nums[i]]++; ----------->            m.put(num,m.getorDefault(num,0)+1);

for (auto it : m) max_freq = max(max_freq, it.second);  ----------->            for(int freq : m.values()) max_freq = Math.max(max_freq, freq);
