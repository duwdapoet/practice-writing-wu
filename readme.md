# Tả người thầy "thân yêu" của tôi
##### Người thầy mà tôi muốn nói dến trong bài viết này đó là thầy HVC a.k.a Idol dược các anh em hết mực "yêu quý" trong trường K giấu tên. Thầy không chỉ là một người thầy TẬN TÂM trong công việc mà còn một người biết cách truyền tải kiến thức bến ngoài cho học sinh.
#####       VD: Công ty thầy hồi năm 20xx mua cái siêu máy tính hết 14 tỷ, lúc đó không ai biết dùng phải cử thầy...
##### Ngoài ra, với vốn kiến thức sâu Vô Cùng Lớn của mình. Thầy đã giúp anh em trường K học tốt 8086 - thứ mà chúng tôi đ*o có thi cuối kỳ. Ví dụ:
---
##### .MODEL SMALL
##### .STACK
##### .DATA
#####    TB1    db    "Hay nhap mot ky tu: $"
#####    TB2    db    0DH,0AH,"Ky tu da nhap: $"
#####    KT     db    ?
##### .CODE
#####    MAIN PROC
#####        MOV AX,@DATA
#####        MOV DS,AX
#####        LEA DX, TB1
#####        MOV AH, 9           
#####        INT 21H
#####        MOV AH, 1       
#####       INT 21H    
#####       MOV KT, Al
#####        LEA DX, TB2
#####        MOV AH, 9       
#####        INT 21H
#####        MOV AH, 2       
#####        MOV DL, KT
#####        INT 21H
#####        MOV AH, 4CH
#####        INT 21H
#####    MAIN ENDP
#####    END MAIN
---
##### Tóm lại, thầy HVC là người mà tôi và anh em rất yêu quý.
