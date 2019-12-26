# -*- coding: utf-8 -*-
"""
Created on Thu Dec 19 11:04:37 2019

@author: Lab User
"""

def Binary(List,k,l,h):
    if l==h:
        if List[l]==k:
            return l
        else:
            return 0
    else:
        mid=(l+h)//2
        if k==List[mid]:
            return mid
        if k<List[mid]:
            return Binary(List,k,l,mid-1)
        else:
            return Binary(List,k,mid+1,h)
        
# another method 
def BinarySearch(List,n,key):
    l=0
    h=len(List)-1
    while(h>=l):
        mid=(l+h)//2
        if List[mid]==key:
            return mid
        if key<List[mid]:
            h=mid-1
        else:
            l=mid+1
    return 0
            
        