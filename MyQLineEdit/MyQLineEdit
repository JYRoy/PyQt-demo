class MyQLineEdite(QLineEdit):
    
    def __init__(self):
        super(MyQLineEdite, self).__init__()

    def mouseMoveEvent(self, mouse_event):
        '''
        重写鼠标的左键右键选中
        :param mouse_event: 
        :return: 
        '''
        if mouse_event.buttons == Qt.LeftButton or  mouse_event.buttons() == Qt.RightButton:
            return
        
    def keyPressEvent(self, key_event):
        '''
        重写键盘的全选，复制粘贴
        :param key_event: 
        :return: 
        '''
        if key_event == QKeySequence.SelectAll:  #禁止全选
            return 
        if key_event == QKeySequence.Paste:  #禁止粘贴
            return 
        if key_event == QKeySequence.Copy:  #禁止复制
            return
