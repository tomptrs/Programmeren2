# Programmeren2

## Herhalingsoefeningen

Oefening 2 : de kikker

Public Class Form1

    Private arr() As Integer
    Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click

        InitArray(20)
        Dim waarde = Test(arr, 4)

    End Sub

    Public Sub InitArray(value As Integer)

        ReDim Preserve arr(value)

        For i As Integer = 0 To value
            arr(i) = CInt(Math.Ceiling(Rnd() * 10))
        Next

    End Sub

    Public Function Test(arr() As Integer, x As Integer) As Integer

        Dim teller As Integer = 0

        For i As Integer = 0 To arr.Length - 1

            If arr(i) > 0 Then
                teller = teller + 1
            Else
                teller = -1
                i = arr.Length

            End If

        Next

        Return teller

    End Function

## Cheat Sheet VB.NET

## Tel paren auto's

 Dim autos() As Integer = {0, 1, 0, 1, 1}
        Dim count = 0

        For i As Integer = 0 To autos.Length - 1
            If autos(i) = 0 Then
                For j As Integer = i To autos.Length - 1
                    If autos(j) = 1 Then
                        count = count + 1
                    End If
                Next
            End If
        Next
        MessageBox.Show(count)
