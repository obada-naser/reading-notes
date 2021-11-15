# RecyclerView

when we need to display a huge amount of data in our app then we can take advantage of the recyclerView that it can take many data and view them in our app with only asking us to describe how the item looks like and if the item was removed then it stores the view for other items for the future that can make our app more efficient with power and faster.



When we talk about RecyclerView we have a several classes that can be mentioned such as:
* ViewGroup and it is where view that have the data is.
* ViewHolder and that means for each element there is a viewHolder to show it.
* adaptor and it is where the recyclerView gets its methods.
* LayoutManager where the elements appear in order.


## Using the RecyclerView

there three steps we need to be able to start using the recycleView:
1. Because of the huge amount of elements we need to show them in a specific arrangement like grid or list.
2. Then we dig to each element how it will be displayed .
3. lastly to get the methods and get the data to be able to appear.


## layout arrangement
We can arrange the items using three types of layout managers such as:
* LinearLayoutManager: used to arrange in a one dimensional arrangement for the items.
* GridLayoutManager: used to the arrange them in two-dimensional and depends if the grid is vertical or horizontal.
* StaggeredGridLayoutManager :it has the same functionality as GridLayoutManager with a little modifications.


finally, we need to define two things to make the recycleViewer to work in a perfect way one is the adaptor that creates the ViewHolder and in turn the ViewHolder is the container for the views that in turn contains the layout for each item. also, the adaptor bind the views with data and override these methods:onCreateViewHolder(),onBindViewHolder(),getItemCount().
