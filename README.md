# HorizontalScrollTableView
This is a demo for horizontal scroll tableView.
CollectionCell can eazy help you create a horizontal scroll tableView. 

# Install
Just drag collectionCell.h/.m to your project.

# Use it
You need to implement CollectionCellDelegate in your project.


```objective-c
- (UICollectionViewCell *)collectionViewCell:(CollectionViewCell *)collectionViewCell 
                      cellForItemAtIndexPath:(NSIndexPath *)indexPath;
                      
- (void)collectionViewCell:(CollectionViewCell *)CollectionViewCell 
  didSelectItemAtIndexPath:(NSIndexPath *)indexPath;
```
