# HorizontalScrollTableView
This is a demo for horizontal scroll tableView.
CollectionViewCell can eazy help you create a horizontal scroll tableView. 

# Install
Just drag CollectionViewCell.h/.m to your project.

# Use it
#### How to configure CollectionViewCell
```objective-c
- (void)configureCollectionViewCellDelegate:(id<CollectionViewCellDelegate>)delegate
                         tableViewIndexPath:(NSIndexPath *)tableViewIndexPath
                                       rows:(int) rows
                              itemClassName:(NSString *)itemClassName
                                  topOffset:(int)topOffset
```
#### Implement CollectionCellDelegate in your project.
```objective-c
- (UICollectionViewCell *)collectionViewCell:(CollectionViewCell *)collectionViewCell 
                      cellForItemAtIndexPath:(NSIndexPath *)indexPath;
                      
- (void)collectionViewCell:(CollectionViewCell *)CollectionViewCell 
  didSelectItemAtIndexPath:(NSIndexPath *)indexPath;
```
