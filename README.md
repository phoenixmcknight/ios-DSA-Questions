# ios-DSA-Questions
func returnValuesFromNodesInLinkedList(head:Node<Int>?) -> [Int] {
    var currentNode = head
    var nodeValueArray:[Int] = []
    while currentNode != nil {
        nodeValueArray.append(currentNode!.value)
        currentNode = currentNode?.next
    }
    return nodeValueArray
}
