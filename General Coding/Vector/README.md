

## Making a 2d-vector

'''
vector<vector<int>> v;
'''

## Taking element in vector
'''
1) v.push_back({start,end});

2) Using for loop 
 
 for(auto &i : a){
    cin>>i;
 }

'''

## Sorting a vector by condition 

1) By making custom function 

'''
bool compare(pair<int,int> p1 , pair<int,int> p2){
    double v1 = (double) p1.first/p2.second;
    double v2 = (double) p2.first/p2.second;

    return v1 > v2;
}

int main(){
vector<pair<int,int>> a;
sort(a.begin() , a.end() , compare);
}
'''

2) Here this code will sort the v in ascending order of v[0].

'''
sort(v.begin() , v.end() , [&](vactor<int> &a, vector<int>&b){
    return a[1] < b[1];
});
'''

