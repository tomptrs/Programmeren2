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
